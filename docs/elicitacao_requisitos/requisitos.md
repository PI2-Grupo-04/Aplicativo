# <center> REQUISITOS DO SISTEMA

#### Histórico de versão<br>

|    Data    |Versão| Descrição | Autor(es)|
| ---------- |------| --------- | -------- |
| 13.08.2021 | 0.1  | Criação do documento | Bruna Almeida |
| 15.08.2021 | 0.2  | Adiciona requisitos funcionais e não funcionais| Bruna Almeida |
| 16.08.2021 | 0.3  | Adiciona objetivo    | Bruna Almeida |
| 20.08.2021 | 0.4  | Adição das Prioridades | Letícia Karla Araújo |
<br>

### Objetivo do documento

<div align="justify">O objetivo do levantamento de requisitos é definir os serviços e funções que o software deve executar. O levantamento de requisitos é fundamental para uma boa execução do projeto do sistema. 
<br><br>
Os requisitos principais do sistema foram levantados pela equipe de software durante um Brainstorming. A técnica de brainstorming - tempestade de ideias - consiste em uma dinâmica em grupo, onde há troca de ideias, para unir informação e estimular o pensamento criativo para resolução de problemas. Durante a dinâmica, todos os integrantes da equipe expuseram sua visão do sistema e o que seria crucial para o sistema.
<br><br>
Posteriormente, foi aplicada a técnica de introspecção, que se baseia em imaginar que tipo de sistema eu iria querer se fosse utilizar o sistema em questão. Foi pedido que cada integrante, individualmente, se imaginasse como usuário do sistema para o robô garçom, e que listasse os requisitos funcionais e não-funcionais que achasse essencial e viável para o software.
<br><br>
Através das duas técnicas de elicitação empregadas, foram levantados os seguintes requisitos funcionais e não funcionais do sistema de software.
</div>
<br>

## Requisitos funcionais

|  ID |Requisito| Prioridade| Pré-Condições|
|-----|---------|---------| -----------|
|RF001|O usuário poderá acessar o aplicativo sem ter login.| Alta| N/A. |
|RF002|O usuário poderá visualizar o cardápio do restaurante.| Alta| RF001 |
|RF003|O usuário poderá visualizar detalhes sobre um item do menu.| Alta| RF002 |
|RF004|O usuário poderá adicionar um item do menu no carrinho do seu pedido.| Alta| RF002 |
|RF005|O sistema deverá ser capaz de mostrar a lista de itens que o usuário adicionou ao seu pedido.| Alta| RF004 |
|RF006|O usuário poderá adicionar observações ao pedido.| Média | RF004 |
|RF007|O usuário poderá adicionar ingredientes extras a um item do seu pedido.| Média | RF004 |
|RF008|O usuário poderá excluir um item no carrinho do seu pedido.| Alta | RF005 |
|RF009|O sistema deverá mostrar o valor total do pedido.| Alta | RF005 |
|RF010|O aplicativo deverá disponibilizar um espaço para o usuário digitar códigos de promoção.| Baixa | RF006 |
|RF011|O sistema deverá mostrar o tempo previsto de espera para o pedido.| Baixa | N/A. |
|RF012|O usuário poderá cancelar o pedido antes do pagamento.| Média | N/A. |
|RF013|O aplicativo deverá mostrar as formas de pagamento disponíveis.| Alta | N/A. |
|RF014|O usuário poderá escolher a forma de pagamento do pedido.| Alta | RF013 |
|RF015|O sistema deverá processar o pagamento feito pelo usuário.| Alta | N/A. |
|RF016|O aplicativo deve permitir fechar pedidos seguidos.| Média | N/A. |
|RF017|O aplicativo deve enviar o comprovante de pagamento para o usuário.| Alta | RF015 |


## Requisitos não funcionais

|  ID |Requisito| Prioridade| Pré-Condições|
|-----|---------| ---------| -----------|
|RNF001|O sistema deve ter segurança para os pagamento via cartão.| Alta | N/A. |
|RNF002|O sistema deve ter segurança para os dados dos clientes.| Alta | RNF001 |
|RNF003|A API deve ser feita via microsserviços.| Baixa | N/A. |
|RNF004|O aplicativo deve se comunicar com o Robô Garçom.| Alta | N/A. |
|RNF005|O aplicativo deve se conectar à internet.| Baixa | N/A. |
|RNF006|O aplicativo deve ser aprovado em testes.| Média | N/A. |
|RNF007|O usuário poderá navegar pelos menus.| Alta | N/A. |
|RNF008|O App deverá ser compatível com normas de acessibilidade e compatibilidade, com solução/assistência/ajuda para debilidades.| Alta | RNF007 |
|RNF009|O App deverá estar de acordo com a LGPD e melhores práticas de segurança.| Alta | RNF002 |
|RNF010|O sistema deverá ser capaz de receber pagamentos através dos serviços Mercado Pago e Pix.| Média | N/A. |
