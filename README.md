# Sistema de Restaurante

Este repositório contém a implementação de um sistema simples de pedidos para um restaurante em C++. O código utiliza estruturas de dados como listas encadeadas para representar o cardápio, a fila de pedidos em andamento e uma lista de pedidos preparados.

**Estruturas de Dados:**
- `Prato`: Estrutura que representa um prato com um nome e um preço.
- `NoLista`: Nó utilizado para construir listas encadeadas, contendo um prato, um ponteiro para o próximo nó e um ponteiro para o nó anterior.
- `DescritorLista`: Descritor de lista encadeada que mantém ponteiros para o início e fim da lista, além do tamanho.
- `DescritorFila`: Descritor de fila que mantém ponteiros para o início e fim da fila, além do tamanho.

**Funções Principais:**
1. `criarLista()`: Função para criar uma lista encadeada vazia.
2. `criarFila()`: Função para criar uma fila vazia.
3. `adicionarPrato()`: Adiciona um prato ao cardápio (lista encadeada).
4. `adicionarPedidoAndamento()`: Adiciona um pedido em andamento à fila, verificando se o prato está no cardápio.
5. `processarPedido()`: Processa pedidos da fila e move-os para a lista de pedidos preparados.
6. `entregarPedido()`: Entrega pedidos da lista encadeada.
7. `cancelarPedido()`: Cancela pedidos em andamento na fila.
8. `verificarPratoNoCardapio()`: Verifica se um prato está no cardápio.
9. `contarPedidos()`: Função recursiva para contar o total de pedidos.
10. `inicializarCardapio()`: Inicializa o cardápio com alguns pratos.
11. `exibirMenu()`: Exibe o menu principal e retorna a escolha do usuário.

**Funcionalidades do Programa:**
- Adição de pedidos ao cardápio.
- Cancelamento de pedidos em andamento.
- Processamento de pedidos para a lista de pedidos preparados.
- Entrega de pedidos preparados.
- Verificação de disponibilidade de pratos no cardápio.
- Contagem total de pedidos feitos durante a execução.

**Instruções de Uso:**
- Execute o programa e siga as opções do menu para interagir com o sistema de pedidos.
- Os pratos disponíveis inicialmente estão listados no cardápio.

**Notas Importantes:**
- O código inclui marcações para implementações específicas que podem variar conforme a necessidade do restaurante.
- A interação com o usuário é realizada através do console usando `cin` e `cout`.
- Certifique-se de liberar a memória alocada ao final do programa.

**Contribuições:**
- Contribuições são bem-vindas! Sinta-se à vontade para abrir problemas ou solicitar funcionalidades adicionais.
