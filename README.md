# Modelagem-de-dados
Projeto - Desafio modelagem de dados - E-comerce 
Objetivo:
Refine o modelo apresentado acrescentando os seguintes pontos:

Cliente PJ e PF – Uma conta pode ser PJ ou PF, mas não pode ter as duas informações;
Pagamento – Pode ter cadastrado mais de uma forma de pagamento;
Entrega – Possui status e código de rastreio;

Narrativa:
Scopo:  Venda de Produtos 

Produtos: 
*Os produtos são vendidos por uma unica plataforma online.  Contudo estes podem ter vendedores dostintos(terceiros)
*cada produto possui um fornecedor 
*Um ou mais produtos podem compor um pedido 

Clientes:
*O cliente pode se cadastrar no site com o seu CPF ou CNPJ
*O endereço do Cliente irá determinar o Valor do Frete 
*Um cliente pode fazer mais de um pedido. Este tem um periodo de carencia para devolução do produto 

Pedido:
*O pedido são criados por clientes e possuem informações de compra endereço e status de Entrega.
*Um produto ou mais compoem o pedido.
*O pedido pode ser cancelado

