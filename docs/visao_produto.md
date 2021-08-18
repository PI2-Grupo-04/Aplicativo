# <center> VISÃO DE PRODUTO

#### Histórico de versão<br>

|    Data    | Versão | Descrição | Autor(es)|
| ---------- | ------ | --------- | -------- |
| 18.08.2021 |   0.1  | Adiciona Primeira versão do Docuemnto de Visão | Samuel Borges |


## Objetivo do documento

O objetivo deste documento é facilitar o entendimento geral do produto, suas
necessidades, escopos e riscos. Além disso, esse documento é apresentado em um
alto nível de abstração para facilitar o entendimento para todos os envolvidos em
sua produção.

<br>

## Visão de produto

### **Aplicativo**:
O aplicativo tem como objetivo facilitar pedidos e entregas de comida em um
restaurante em que o consumo se dá no local, evitando falhas de comunicação entre 
o cliente e o atendente além de evitar contato humano desnecessário, que pode
transmitir doenças contagiosas, principalmente em períodos de pandemia.

### **Robô**:
O robô irá realizar as entregas dos alimentos solicitados pelo aplicativo. 
O *layout* do restaurante será mapeado de antemão e o robô realizará suas entregas
de forma algorítmica. O objetivo do robô é evitar o contato humano na hora da
entrega de alimentos, além de idealmente diminuir o custo do restaurante com
mão de obra.

<br>

## Posicionamento

### **Oportunidade de Negócios:**
Atualmente estamos vivendo um período delicado causado pela pandemia do COVID-19.
Por isto, se tornaram necessárias inovações que permitam o funcionamento de
determinados setores da economia enquanto reduzem as possibilidades de infeccção.
Os aplicativos de entrega de comida resolveram parte deste problema, mas
restaurantes de consumo local muitas vezes tiveram que arranjar soluções
provisórias de baixa qualidade, com muitos deles utilizando serviços em núvem para
armazenar imagens ou PDFs de seus cardápios que poderiam ser acessados por meio de
um QR code.


### **Descrição do problema:**

<br>

<table>
  <tr>
    <th> O problema </th>
    <td> A necessidade de pessoas anotando e entregando pedidos em restaurantes. </td>
  </tr>
  <tr>
    <th> Afeta </th>
    <td>
      Restaurantes que precisam funcionar mesmo tendo que reduzir contato humano ou
      mão de obra.
    </td>
  </tr>
  <tr>
    <th> cujo impacto é </th>
    <td> Aumento da possibilidade de contagio e gastos com mão de obra. </td>
  </tr>
  <tr>
    <th> Uma boa solução seria </th>
    <td>
      Um sistema automatizado para resolver simultâneamente o problema de realização e
      entrega de pedidos
    </td>
  </tr>
</table>
<br>

### **Sentença de Posição do Produto:**

<table>
  <tr>
    <th> Para </th>
    <td> Restaurantes que oferecem consumo primariamente no local </td>
  </tr>
  <tr>
    <th> Que </th>
    <td>
      Necessitam de alguma maneira de evitar contato humano entre garçons e clientes
      ou diminuir os custos com mão de obra 
    </td>
  </tr>
  <tr>
    <th> O </th>
    <td> Projeto Robô Garçom </td>
  </tr>
  <tr>
    <th> Que </th>
    <td> Oferece um sistema automatizado de pedido e entrega de alimentos </td>
  </tr>
  <tr>
    <th> Diferente dos </th>
    <td> Aplicativos de entrega de comida tradicionais como iFood e UberEats </td>
  </tr>
  <tr>
    <th> Nosso produto </th>
    <td>
      Foca em restaurantes com o consumo no local e vem integrado com um robô
      entregador
    </td>
  </tr>
</table>

<br>

### **Resumo dos usuários:**
| Nome | Descrição | Responsabilidades | Envolvido |
| ---- | --------- | ----------------- | --------- |
| Administrador | Usuário com autorização de criar entidades | Responsável por criar e atualizar cardápios do restaurante | Dono e ou gerente do restaurante|
| Usuário Comum | Usuário que irá consumir os dados da aplicação | Fazer pedidos e realizar pagamentos | Consumidores |

<br>

## Escopo

### **Aplicativo:**
Os itens a seguir fazem parte do escopo do Aplicativo:

- Interface de escolha de alimentos;
- Escolha de métodos de pagamentos;
- Processamento do pagamento (Consumo de serviço de terceiros);
- Emissão de comprovante de pagamento;
- Cupons de desconto.

### **Robô:**
Os itens a seguir fazem parte do escopo do Robô:
- Navegação algorítimica;
- Detecção de obstruçoes no caminho;
- Aviso de obstrução de caminho.

<br>

## Escopo negativo
### **Aplicativo:**
Os itens a seguir **NÃO** fazem parte do escopo do Aplicativo:

- Recomendação de restaurantes;
- Recomendação de pratos.

### **Robô:**
Os itens a seguir **NÃO** fazem parte do escopo do Robô:

- Machine learning para navegação automática pelo restaurante;
- Viagens de longas distâncias.

<br>

## Referências
- SOMMERVILLE, Ian. Engenharia de Software. São Paulo: Pearson Prentice Hall. 9ª edição. 2011.

- GUEDES, Gilleanes T. A. UML: uma abordagem prática. Novatec Editora, 2008.