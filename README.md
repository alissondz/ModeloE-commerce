# Modelo E-commerce
## Uma breve descrição do projeto.
 Este projeto representa um modelo de banco de dados para um sistema de e-commerce. A seguir, está uma descrição detalhada de cada entidade e suas relações:

## Cliente:
 Representa os clientes do sistema, contendo informações como nome e endereço. Existem duas subclasses:

## ClientePF:
Contém informações adicionais para clientes pessoa física (CPF e nome completo).
ClientePJ: Contém informações adicionais para clientes pessoa jurídica (CNPJ e razão social).
FormaPagamento: Representa os diferentes métodos de pagamento disponíveis no sistema, incluindo detalhes como tipo e informações adicionais do pagamento.

## ClienteFormaPagamento:
 Relaciona os clientes com suas formas de pagamento preferidas.

## Pedido:
 Registra os pedidos realizados pelos clientes, incluindo status, descrição, frete e referência ao cliente que fez o pedido.

## Relacao de produto/pedido:
 Relaciona os produtos aos pedidos, especificando a quantidade de cada produto em um pedido.

## Entrega:
 Contém informações sobre a entrega dos pedidos, como status, código de rastreio e a referência ao pedido associado.

## Produto: 
Representa os produtos disponíveis para venda no e-commerce, com atributos como categoria, descrição e valor.

## Estoque:
 Representa os locais de estoque dos produtos.

## Produto_has_Estoque:
Relaciona os produtos com seus respectivos estoques, especificando a quantidade de cada produto em cada local de estoque.

## Fornecedor:
 Representa os fornecedores dos produtos, contendo informações como razão social e CNPJ.

## Disponibilizando um produto:
 Relaciona os fornecedores com os produtos que eles fornecem.

## Terceiro - vendedor:
 Representa os vendedores terceirizados que podem vender produtos no sistema, incluindo razão social e localização.

## Produtos por vendedor(terceiro): 
Relaciona os vendedores terceirizados com os produtos que eles vendem, especificando a quantidade disponível.

### A estrutura do banco de dados é desenhada de maneira a garantir a integridade e a eficiência na gestão das informações de um sistema de e-commerce, cobrindo desde o cadastro dos clientes e fornecedores até a gestão de pedidos, entregas e estoque de produtos.