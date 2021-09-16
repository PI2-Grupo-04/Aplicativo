# <center> ARQUITETURA DE SOFTWARE

#### Histórico de versão<br>

|      Data      | Versão | Descrição | Autor(es)|
| -------------- | --------- | --------- | -------- |
| 16.09.2021     |    0.1    | Criação do documento| Bruna Almeida |
<br>

### Objetivo do documento

<div align="justify"> O presente documento visa apresentar as decisões que foram tomadas pela equipe quanto à arquitetura do software que será desenvolvido para o projeto <b>Robô Garçom</b>.
<br>
As escolhas quanto à arquitetura do software se deram levando em consideração a facilidade de integração entre os componentes. Um exemplo disso é a escolha da linguagem JavaScript, que é a mesma utilizada no Framework <b>Johnny Five</b>, que fará integração entre o robô e o computador central da cozinha.
<br></div>


## Arquitetura do Software

<div align="justify">
O software proposto para o projeto será uma aplicação estruturada no modelo arquitetural <b>MVC</b> (Model-View-Controller), e permitirá que os clientes, por meio de um tablet disponível em cada mesa, visualizem o cardápio, façam seus pedidos e realizem o pagamento, através das plataformas Mercado Pago ou PIX.
<br>
A arquitetura MVC permite dividir as funcionalidades do sistema em camadas, o que facilita a resolução de um problema maior. As camadas consistem em:<br></div>

- <div align="justify"><b>Modelo (Model):</b> Sua responsabilidade é gerenciar e controlar a forma como os dados se comportam por meio das funções, lógica e regras de negócios estabelecidas. É a camada que se comunica com o banco de dados, recebe as informações do Controlador, válida se ela está correta ou não e envia a resposta mais adequada.</div>

- <div align="justify"><b>Visualização (View):</b> Responsável por tudo que o usuário final visualiza, toda a interface e recursos ligados a aparência como mensagens, botões ou telas \cite{padraoMVC2}. Transmite questionamentos ao \textit{controller} e entrega as respostas obtidas ao usuário.</div>

- <div align="justify"><b>Controlador (Controller):</b> Responsável por controlar todo o fluxo de informação que passa pelo sistema. É a camada que executa uma regra de negócio e repassa a informação para a visualização.</div>

<div align="justify">O diagrama de blocos a seguir representa a arquitetura do sistema, integrando o Robô Garçom a todo o sistema de automação do restaurante.
<br></div>

<br>
<div align="center"><img src="../../imagens/diagrama_blocos.png" width="700" ></<br>
<figcaption align='center'>
    <b>Figura 1 - Diagrama de blocos desenvolvido para o projeto Robô Garçom. Fonte: autores.</b>
</figcaption>
<br></div>

<div align="justify">A escolha do MVC como a arquitetura do sistema se deu pelo fato dessa arquitetura proporcionar uma separação clara entre as camadas de visualização e regras de negócios, o que torna mais fácil a manutenção do sistema.<br></div>


## Linguagem

<div align="justify">A aplicação será desenvolvida em <b>JavaScript (JS)</b>, uma linguagem leve, interpretada e baseada em objetos com funções de primeira classe, ou seja, os objetos são criados dinamicamente, destruídos, transmitidos para uma função, retornados como um valor e têm todos os direitos que outras variáveis da linguagem de programação possuem. JS é conhecido como a linguagem de script para páginas Web, mas também é utilizada em vários outros ambientes sem browser, como por exemplo o node.js.
<br>
De acordo com o site stackoverflow.com, JS foi eleito pelo oitavo ano seguido a linguagem de programação mais usada no mundo. Sua popularidade é uma consequência por ela ser uma linguagem muito flexível e multifacetada.
<br>
Uma das vantagens de se utilizar o JS é a existência de um Framework voltado ao controle de robôs, denominado Johnny Five, para integração direta com os controladores utilizados no equipamento, e que é escrito em JavaScript, o que facilita a produção do software.
<br></div>

## Front-end e Back-end

<div align="justify">
A definição das ferramentas utilizadas para o desenvolvimento do Back e Front-end, se deu por conta da familiaridade da equipe com as plataformas NodeJS e React, ambos utilizados para a execução de códigos JavaScript.
<br>
A biblioteca <b>React</b> será utilizada para o desenvolvimento da interface do usuário (front-end). Trata-se de de uma biblioteca de código aberto escrita em JavaScript, e será utilizada no desenvolvimento do sistema, em conjunto com o módulo <b>React Native</b>, que possibilita o desenvolvimento de aplicativos para Android e iOS. Essa ferramenta foi definido para o desenvolvimento da interface do sistema por sua flexibilidade - facilidade de integração com outras bibliotecas e Frameworks - e pelo uso de componentes reutilizáveis.
<br>
Já para o back-end será utilizado o <b>Node.JS</b>. Node é uma plataforma de aplicação, na qual os programas são escritos em JS e compilados, otimizados e interpretados pela Máquina Virtual V8, que é a mesma usada pelo Google para executar JavaScript no navegador Chrome. O resultado deste processo é entregue como código de máquina server-side, tornando o Node muito mais eficiente na sua execução e consumo de recursos . O Node.JS será utilizado em conjunto com o Framework <b>Express.JS</b>.
<br>
A plataforma Node foi escolhida por ser eficiente na implementação de aplicações em tempo real, que precisam transferir mensagens de um lado para o outro de forma rápida. As mensagens no caso do sistema Robô Garçom, serão os pedidos. Além disso, o NodeJS é uma API com NoSQL por trás, o que facilita a integração com o banco de dados MongoDB.
<br></div>

## Banco de dados

<div align="justify">
O banco de dados utilizado para a aplicação será o <b>MongoDB</b>, um banco do tipo NoSQL. Por ser um banco de dados do tipo NoSQl, o MongoDB é orientado a documentos, ou seja, armazena todos os dados em arquivos do tipo JSON, ao contrário do modelo de dados relacional que armazena os dados em linhas e colunas. O MongoDB é ágil e escalável horizontalmente e também permite consultas diretas com JavaScript.
<br>
Para gerenciar e armazenar todas as informações utilizadas pelo robô e o restaurante, o bando de dados MongoDB se mostrou a alternativa mais adequada, já que é escalável horizontalmente, o que permite a ampliação de todo o seus sistema caso seja necessário. Suporta também um alto índice de consultas e envios de dados em JavaScript, pois trata-se de um banco do tipo NoSQL.
<br></div>
<br>

### Referências

- WAGON le. **O que é padrão MVC? Entenda arquitetura de softwares!**. 2020. Disponível em: [lewagon.com/pt-BR/blog/o-que-e-padrao-mvc](https://www.lewagon.com/pt-BR/blog/o-que-e-padrao-mvc). Acesso em 07 desetembro de 2021.

- NET, O. D. **O que é Model-view-controller (MVC)?**. 2011. Disponível em: [oficinadanet.com.br/artigo/desenvolvimento/o_que_e_model-view-controller_mvc](https://www.oficinadanet.com.br/artigo/desenvolvimento/o_que_e_model-view-controller_mvc). Acesso em 07 desetembro de 2021.

- OVERFLOW, **S.Most Popular Technologies: programming, scripting, and markup languages.**. 2021. Disponível em: [insights.stackoverflow.com/survey/2020#most-popular-technologies](https://insights.stackoverflow.com/survey/2020#most-popular-technologies). Acesso em 07 de setembro de 2021.

- ESCUDELARIO, B. de F. **Vale a pena aprender NodeJS?**. 2018. Disponível em: [imasters.com.br/back-end/vale-pena-aprender-nodejs](https://imasters.com.br/back-end/vale-pena-aprender-nodejs). Acesso em 07 de setembro de 2021.