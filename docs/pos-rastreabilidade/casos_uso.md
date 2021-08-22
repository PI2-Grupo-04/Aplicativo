# <center> CASOS DE USO

#### Histórico de versão<br>

| Data       | Versão | Descrição             | Autor(es)     |
| ---------- | ------ | --------------------- | ------------- |
| 00.08.2021 | 0.1    | Adiciona Casos de Uso | Samuel Borges |

### Objetivo do documento

<div align="justify">

<br><br></div>

## Casos de uso

<div align="justify">

### UC01 Manter Usuário do Restaurante

**Ator:** Dono/Gerente do Restaurante

**Descrição:** Permite que o usuário faça cadastro, visualize, edite e delete o
seu perfil como administrador do restaurante.

**Pré-condições:** Usuário deve ter um dispositivo com acesso ao aplicativo e entrar em contato com a equipe responsável pelo serviço do Robô garçom.

**Pós-condições:** Qualquer alteração feita pelo usuário deve ser salva no sistema

**Fluxo normal:**

1. O usuário administrador entra no aplicativo e realiza login;
1. O usuário administrador entra na tela do perfil;
1. O usuário administrador edita as informações ali presentes;
1. O usuário administrador salva o perfil e retorna à pagina inicial.

<br><br>

### UC02 Manter Cardápio do Restaurante

**Ator:** Dono/Gerente do Restaurante

**Descrição:** Permite que o usuário administrador faça o cadastro, visualize, edite e delete o cardápio do seu restaurante.

**Pré-condições:** O usuário administrador deve ter uma conta no sistema e um
aparelho com acesso ao sistema.

**Pós-condições:** Qualquer alteração feita ao cardápio do restaurante deve ser
salva no sistema.

**Fluxo normal:**

1. O usuário administrador entra no aplicativo e realiza login;
1. O usuário administrador entra na tela do cardapio do restaurante;
1. O usuário administrador edita as informações dobre o cardápio;
1. O usuário administrador salva o cardápio e retorna à tela inicial.

<br><br>

### UC03 Visualizar o Cardápio

**Ator:** Usuário Comum

**Descrição:** Permite que o Usuário comum visualize o cardápio do retaurante em
que se encontra.

**Pré-condições:** O usuário deve ter um aparelho com acesso ao aplicativo.

**Pós-condições:** O usuário deve conseguir ver na tela de seu aparelho o cardápio
do restaurante em que se encontra.

**Fluxo normal:**

1. O usuário entra no sistema e busca o cardápio do restaurante em que se encontra;
1. O usuário visualiza o cardápio do restaurante.

<br><br>

### UC04 Visualizar Item do Cardápio

**Ator:** Usuário Comum

**Descrição:** Permite que o usuário comum veja detalhes sobre cada item no
cardápio

**Pré-condições:** O usuário precisa estar visualizando o cardápio do restaurante.

**Pós-condições:** O usuário consegue ver na tela de seu aparelho os detalhes
sobre um item específico do cardápio.

**Fluxo normal:**

1. O usuário visualiza o carcápio do restaurante em que se encontra;
1. O usuário seleciona o item que deseja detalhar e aciona a opção "Mais Detalhes";
1. O usuário vê os detalhes do item escolhido.

<br><br>

### UC05 Manejar Itens no Carrinho

**Ator:** Usuário Comum

**Descrição:** Permite que o usuário comum adicione, edite e remova itens do seu
carrinho

**Pré-condições:** O usuário precisa ter acesso ao cardápio do restaurante.

**Pós-condições:** Qualquer adição, edição ou remoção de itens no carrinho precisa
ser salva no sistema.

**Fluxo normal:**

1. O usuário visualiza os itens do cardápio do restaurante em que se encontra;
1. O usuário adiciona os itens que quer no seu carrinho;
1. O usuário edita ou remove qualquer item no seu carrinho;
1. O usuário finaliza o pedido.

<br><br>

### UC06 Adicionar observações aos Itens do Pedido

**Ator:** Usuário Comum

**Descrição:** Permite que o usuário comum adicione, edite e remova observações
sobre cada item do seu pedido

**Pré-condições:** O usuário precisa ter itens adicionados ao seu carrinho.

**Pós-condições:** As observações de cada item são salvas no sistema.

**Fluxo normal:**

1. O usuário adiciona um item ao seu carrinho;
1. O usuário pode adicionar uma observação a esse item;
1. O usuário salva a observação para esse item.

<br><br>

### UC07 Incrementar Itens do Pedido

**Ator:** Usuário Comum

**Descrição:** Permite que o usuário comum incremente cada item do seu pedido com
ingredientes extras.

**Pré-condições:** O usuário precisa ter itens adicionados ao seu carrinho.

**Pós-condições:** Os ingredientes extras de cada item são salvas no sistema.

**Fluxo normal:**

1. O usuário adiciona um item ao seu carrinho;
1. O usuário pode adicionar ingredientes extras a esse item;
1. O usuário salva a observação para esse item.

<br><br>

### UC08 Visualizar Itens do Pedido

**Ator:** Usuário Comum

**Descrição:** Permite que o usuário comum visualize todos os itens do seu pedido
antes da realização do pagamento.

**Pré-condições:** O usuário precisa ter itens adicionados ao seu carrinho.

**Pós-condições:** A lista de itens que o usuário adicionaou em seu carrinho vão
ser exibidas na tela do aparelho.

**Fluxo normal:**

1. O usuário adiciona um ou mais itens ao seu carrinho;
1. O usuário vê os itens que adicionou ao carrinho.

<br><br>

### UC09 Realizar Pedido

**Ator:** Usuário comum

**Descrição:** Permite que o usuário envie o seu pedido para ser preparado pelo
restaurante.

**Pré-condições:** O usuário precisa ter itens adicionados ao seu carrinho.

**Pós-condições:** O usuário é encaminhado para a tela de pagamento.

**Fluxo normal:**

1. O usuário adiciona um ou mais itens ao seu carrinho;
1. O usuário vê os itens que adicionou ao carrinho;
1. O usuário confirma os itens que estão no carrinho;
1. O usuário é encaminhado para a tela de pagamento.

<br><br>

### UC10 Cancelar Pedido

**Ator:** Usuário Comum

**Descrição:** Permite que o usuário cancele um pedido antes de realizar o
pagamento

**Pré-condições:** O Usuário precisa ter feito um pedido.

**Pós-condições:** O pedido é cancelado.

**Fluxo normal:**

1. O usuário faz um pedido e é encaminhado para a tela de pagamento;
1. O usuário cancela o pedido;
1. O usuário é encaminhado para a tela do cardápio.

<br><br>

### UC11 Processar Pagamento

**Ator:** Usuário Comum

**Descrição:** Permite que o usuário escolha o método de pagamento e realize o
pagamento.

**Pré-condições:** O Usuário precisa ter feito um pedido.

**Pós-condições:** O pedido é pago e enviado para o preparo pelo restaurante.

**Fluxo normal:**

1. O usuário faz um pedido e é encaminhado para a tela de pagamento;
1. O usuário realiza o pagamento do pedido;
1. O pedido é enviado para o preparo pelo restaurante.

<br><br>

### UC12 Visualizar pedidos pagos

**Ator:** Usuário Comum

**Descrição:** Permite que o usuário comum veja seus pedidos pagos e exporte o
comprovante do pagamento de um pedido feito anteriormente.

**Pré-condições:** O usuário precisa ter realizado o pagamento de um pedido.

**Pós-condições:** O comprovante do pedido é gerado e exportado.

**Fluxo normal:**

1. O usuário realiza o pagamento do pedido;
1. O pedido é enviado para o preparo pelo restaurante;
1. O usuário navega para a tela de pedidos pagos;
1. O usuário vê os detalhes de um pedido específico e exporta o comprovante de pagamento.

<br><br>

### UC13 Visualizar tempo restante de espera

**Ator:** Usuário Comum

**Descrição:** Permite que o usuário comum visualize o tempo restante estimado
para a entrega do seu pedido.

**Pré-condições:** O usuário precisa ter feito e pago um pedido.

**Pós-condições:** O usuário vê o tempo restante estimado para a entrega do pedido.

**Fluxo normal:**
1. O usuário realiza o pagamento do pedido;
1. O pedido é enviado para o preparo pelo restaurante;
1. O usuário vê o tempo restante estimado para a entrega do pedido.

<br><br></div>
