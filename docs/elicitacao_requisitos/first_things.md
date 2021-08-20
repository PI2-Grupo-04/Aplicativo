# <center> FIRST THINGS FIRST

#### Histórico de versão<br>

|    Data    | Versão | Descrição | Autor(es)|
| ---------- | ------ | --------- | -------- |
| 18.08.2021 |   0.1  | Adiciona First Things First | Samuel Borges |


## Objetivo do documento



O objetivo deste documento é realizar uma priorização dos requisitos utilizando um 
levantamento de dados de benefícios, custos e riscos relacionados a cada um deles.

Os dados são calculados utilizando o passo a passo a seguir:
1. Estimar o Beneficio Relativo que cada requisito oferece ao produto de 1 a 9;
1. Estimar a Penalidade Relativa que a falta de cada requisito oferece a aplicação de 1 a 9;
1. Achar o Valor total de cada requisito usando a formula `Valor Total = Benefício relativo + Penalidade Relativa`;
1. Estimar o Custo de implementação de cada requisito;
1. Estimar o Risco Técnico da implementação de cada requisito;
1. Calcular a prioridade utilizando a fórmula `Prioridade = Valor Total% / (Custo% + Risco%)`




## First Things First


|  ID |Requisito| Benefício Relativo | Penalidade Relativa | Valor Total | Custo Estimado | Risco Estimado | Prioridade |
|-----|---------|--------------------|---------------------|-------------|----------------|----------------|------------|
|RF001|O usuário poderá acessar o aplicativo sem ter login.| 9 | 9 | 18 | 2 | 1 | 1.275 |
|RF002|O usuário poderá visualizar o cardápio do restaurante.| 9 | 9 | 18 | 2 | 1 | 1.275 |
|RF013|O aplicativo deverá mostrar as formas de pagamento disponíveis.| 9 | 9 | 18 | 2 | 3 | 0.765 |
|RF014|O usuário poderá escolher a forma de pagamento do pedido.| 9 | 9 | 18 | 2 | 3 | 0.765 |
|RF009|O sistema deverá mostrar o valor total do pedido.| 9 | 9 | 18 | 2 | 3 | 0.765 |
|RF012|O usuário poderá cancelar o pedido antes do pagamento.| 9 | 9 | 18 | 2 | 3 | 0.765 |
|RF003|O usuário poderá visualizar detalhes sobre um item do menu.| 9 | 9 | 18 | 4 | 3 | 0.546 |
|RF004|O usuário poderá adicionar um item do menu no carrinho do seu pedido.| 9 | 9 | 18 | 4 | 3 | 0.546 |
|RF005|O sistema deverá ser capaz de mostrar a lista de itens que o usuário adicionou ao seu pedido.| 8 | 9 | 17 | 4 | 3 | 0.546 |
|RF008|O usuário poderá excluir um item no carrinho do seu pedido.| 9 | 9 | 18 | 4 | 3 | 0.546 |
|RF011|O sistema deverá mostrar o tempo previsto de espera para o pedido.| 7 | 5 | 12 | 2 | 3 | 0.51 |
|RF016|O aplicativo deve permitir fechar pedidos seguidos.| 8 | 8 | 16 | 4 | 3 | 0.486 |
|RF006|O usuário poderá adicionar observações ao pedido.| 6 | 4 | 10 | 2 | 3 | 0.425 |
|RF017|O aplicativo deve enviar o comprovante de pagamento para o usuário.| 9 | 9 | 18 | 6 | 3 | 0.425 |
|RF007|O usuário poderá adicionar ingredientes extras a um item do seu pedido.| 6 | 4 | 10 | 4 | 3 | 0.304 |
|RF015|O sistema deverá processar o pagamento feito pelo usuário.| 9 | 9 | 18 | 8 | 9 | 0.225 |
|RF010|O aplicativo deverá disponibilizar um espaço para o usuário digitar códigos de promoção.| 6 | 4 | 10 | 6 | 6 | 0.177 |



### Referências
<!-- se tiver referencias -->
- LEONHARDT, Rodrigo. Priorização #02 — MoSCoW. Medium. Disponível em: https://medium.com/gerindo-produtos-digitais/prioriza%C3%A7%C3%A3o-02-moscow-84362fbc9350. Acesso em: 18 de agosto de 2021.
- VARGAS, Ana. Priorização de requisitos. Matera. Disponível em: http://www.matera.com/blog/post/priorizacao-de-requisitos. Acesso em: 18 de agosto de 2021.
