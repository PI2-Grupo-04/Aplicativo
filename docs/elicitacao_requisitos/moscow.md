# <center> MOSCOW

#### Histórico de versão<br>

|    Data    |Versão| Descrição | Autor(es)|
| ---------- | ---- | --------- | -------- |
| 15.08.2021 |  0.1 | Criação do documento | Damarcones Porto |
| 16.08.2021 |  0.2 | Adiciona objetivo do documento| Damarcones Porto |
| 16.08.2021 |  0.3 | Adiciona MoSCoW dos requisitos| Damarcones Porto |
<br>

### Objetivo do documento

<div align="justify">
A técnica denominada MoSCoW tem como objetivo priorizar os requisitos levantados pela equipe de software. As quatro letras da palavra MoSCoW significam, respectivamente:<br></div>

- Must have: deve-se ter este requisito, é obrigatório.
- Should have: deveria ter este requisito, é menos importante que <i>Must have</i>.
- Could have: poderia ter este requisito.
- Won't Have: não terá este requisito no momento, mas pode ser implementado mais tarde.
<br>


## MoScoW

### Requisitos funcionais

|  ID |Requisito|MoSCoW|
|-----|---------|------|
|RF001|O usuário poderá acessar o aplicativo sem ter login.|Must|
|RF002|O usuário poderá visualizar o cardápio do restaurante.|Must|
|RF003|O usuário poderá visualizar detalhes sobre um item do menu.|Must|
|RF004|O usuário poderá adicionar um item do menu no carrinho do seu pedido.|Must|
|RF005|O sistema deverá ser capaz de mostrar a lista de itens que o usuário adicionou ao seu pedido.|Should|
|RF006|O usuário poderá adicionar observações ao pedido.|Should|
|RF007|O usuário poderá adicionar ingredientes extras a um item do seu pedido.|Could|
|RF008|O usuário poderá excluir um item no carrinho do seu pedido.|Must|
|RF009|O sistema deverá mostrar o valor total do pedido.|Must|
|RF010|O aplicativo deverá disponibilizar um espaço para o usuário digitar códigos de promoção.|Could|
|RF011|O sistema deverá mostrar o tempo previsto de espera para o pedido.|Could|
|RF012|O usuário poderá cancelar o pedido antes do pagamento.|Should|
|RF013|O aplicativo deverá mostrar as formas de pagamento disponíveis.|Should|
|RF014|O usuário poderá escolher a forma de pagamento do pedido.|Must|
|RF015|O sistema deverá processar o pagamento feito pelo usuário.|Must|
|RF016|O aplicativo deve permitir fechar pedidos seguidos.|Could|
|RF017|O aplicativo deve enviar o comprovante de pagamento para o usuário.|Should|

<br>

### Requisitos não funcionais

|  ID |Requisito|MoSCoW|
|-----|---------|------|
|RNF001|O sistema deve ter segurança para os pagamento via cartão.|Must|
|RNF002|O sistema deve ter segurança para os dados dos clientes.|Must|
|RNF003|A API deve ser feita via microsserviços.|Should|
|RNF004|O aplicativo deve se comunicar com o Robô Garçom.|Must|
|RNF005|O aplicativo deve se conectar à internet.|Should|
|RNF006|O aplicativo deve ser aprovado em testes.|Should|
|RNF007|O usuário poderá navegar pelos menus.|Must|
|RNF008|O App deverá ser compatível com normas de acessibilidade e compatibilidade, com solução/assistência/ajuda para debilidades.|Won't|
|RNF009|O App deverá estar de acordo com a LGPD e melhores práticas de segurança.|Should|
|RNF010|O sistema deverá ser capaz de receber pagamentos através dos serviços Mercado Pago e Pix.|Should|
<br>

### Referências

- WIKIPEDIA, <b>MoSCoW method</b>. Disponível em: <a href="https://pt.wikipedia.org/wiki/MoSCoW_method">wikipedia.org/wiki/MoSCoW_method</a>. Acesso em 16 de agosto de 2021.
