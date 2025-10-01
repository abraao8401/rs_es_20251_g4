# Controle de Produtos e Pedidos

## Objetivo do Projeto
Gerenciar produtos e pedidos, permitindo criar, visualizar, atualizar e deletar registros de produtos e pedidos. Cada pedido está relacionado a um produto existente, e o sistema calcula automaticamente o valor total do pedido.

## Versão
1.0

## Como Iniciar o Projeto
- Execute a classe principal `view.AppView` para abrir a interface JavaFX.
- As abas **Produtos** e **Pedidos** carregam os formulários e tabelas correspondentes automaticamente.

## Autores
Abraão Santiago Moreira

## Instruções para o Usuário

### Produtos
- Utilize os botões **Adicionar**, **Atualizar**, **Deletar**, **Confirmar** e **Cancelar** para gerenciar os produtos.
- Preencha os campos de **Nome**, **Preço** e **Quantidade** conforme necessário.
- A tabela exibe todos os produtos cadastrados e é atualizada automaticamente após cada operação.

### Pedidos
- Selecione um produto existente no `ComboBox` ao criar um pedido.
- Preencha os campos de **Código**, **Quantidade** e **Data do Pedido**.
- O **Valor Total** do pedido será calculado automaticamente com base na quantidade e no preço do produto selecionado.
- Utilize os botões **Adicionar**, **Atualizar**, **Deletar**, **Confirmar** e **Cancelar** para gerenciar os pedidos.
- A tabela exibe todos os pedidos cadastrados e é atualizada automaticamente após cada operação.

## Relacionamento Entre Entidades
- Cada **Pedido** está vinculado a um **Produto** através de seu `id`.
- Produtos podem existir sem pedidos, mas pedidos não podem existir sem um produto associado.

