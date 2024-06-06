# Entidades de Domínio e Casos de Uso

## Entidades de Domínio

Produto
•Atributos: ID único, nome, descrição, tamanho, cor, quantidade em estoque, quantidade mínima de estoque, preço.

Alerta
•Atributos: ID único, tipo (e-mail, notificação do sistema), mensagem, status.

Histórico de Vendas
•Atributos: ID único, produto, quantidade vendida, data da venda, lucro gerado.

Histórico de Estoque
•Atributos: ID único, produto, quantidade em estoque em diferentes datas, tendência de estoque.

Ordem de Compra
•Atributos: ID único, produto, quantidade solicitada, data da ordem, status, fornecedor.

Fornecedor
•Atributos: ID único, nome, informações de contato, prazos de entrega.

Casos de Uso

Rastrear Produto
•Atribuir um número de identificação único a cada produto.
•Adicionar informações adicionais como tamanho e cor.
•Rastrear movimentações de produtos no estoque.

Definir Quantidade Mínima de Estoque
•Definir um limite mínimo para cada produto.
•Atualizar a quantidade mínima de estoque de um produto.

Receber Alertas de Estoque Baixo
•Receber alertas por e-mail quando o estoque estiver baixo.
•Receber notificações no sistema quando o estoque estiver baixo.

Visualizar Histórico de Vendas
•Ver quantos produtos foram vendidos em um determinado período.
•Ver o lucro gerado por produto.
•Identificar quais produtos estão vendendo melhor em cada período.

Visualizar Histórico de Estoque
•Observar a quantidade de estoque de produtos ao longo do tempo.
•Analisar tendências de estoque para auxiliar nas decisões de compra.

Criar e Gerenciar Ordens de Compra
•Criar ordens de compra automaticamente com base nas quantidades mínimas de estoque definidas e nas tendências de vendas.
•Gerenciar o status das ordens de compra.
•Integrar o sistema com fornecedores para receber atualizações sobre prazos de entrega.

Integrar com Fornecedores
•Receber atualizações automáticas dos prazos de entrega de novas remessas.
•Manter informações atualizadas dos fornecedores
