# Casos de Uso – Sistema de Gerenciamento de Estoque

## Gestão de Produtos (CRUD)

- [ ] Cadastrar novo produto
- [ ] Atualizar informações do produto (ex: nome, tamanho, cor, preço)
- [ ] Excluir produto
- [ ] Listar produtos
- [ ] Buscar produto (nome ou ID)
- [ ] Visualizar informações detalhadas de um produto

## Controle de Estoque

- [ ] Registrar entrada de produto no estoque
- [ ] Registrar saída de produto do estoque (venda, perda ou devolução)
- [ ] Listar todas as movimentações de estoque
- [ ] Consultar movimentações de estoque por produto
- [ ] Consultar saldo atual de estoque por produto

## Informações sobre Vendas

- [ ] Registrar nova venda (com todos os produtos comprados nessa venda)
- [ ] Consultar vendas por período ou por produto
- [ ] Obter quantidade total de produtos vendidos
- [ ] Identificar produtos mais vendidos
- [ ] Calcular lucro por produto (se houver preço de custo e venda)

##### (importante que os demais casos de uso estejam em bom funcionamento para os relatórios passarem as informações corretas)

## Relatórios de Vendas

- [ ] Gerar relatório de vendas por período
- [ ] Gerar relatório de vendas por produto
- [ ] Relatório de produtos mais vendidos
- [ ] Relatório de lucro gerado por produto ou período

## Relatórios de Estoque

- [ ] Relatório da quantidade atual em estoque por produto
- [ ] Relatório de movimentações de estoque por período
- [ ] Relatório de produtos com estoque abaixo do mínimo
- [ ] Relatório de produtos com estoque zerado

## Pedido (Solicitações de Compra)

- [ ] Criar nova solicitação de compra (pedido)
- [ ] Visualizar pedidos existentes
- [ ] Atualizar status do pedido (pendente, enviado, recebido)
- [ ] Definir e consultar data de previsão de entrega
- [ ] Associar pedido a fornecedor
- [ ] Gerar pedido automaticamente com base em estoque mínimo e tendências de venda

## Gestão de Usuários

- [ ] Criar conta de usuário
- [ ] Autenticar usuário (login)
- [ ] Atribuir perfil/role ao usuário (ex: operador, gestor)
- [ ] Restringir permissões por role
- [ ] Listar usuários e suas permissões

## Sistema de Alertas

- [ ] Verificar automaticamente produtos com estoque abaixo do mínimo
- [ ] Gerar alerta no sistema para estoque crítico
- [ ] Enviar notificação por e-mail quando estoque estiver baixo ou zerado
- [ ] Marcar alertas como visualizados
- [ ] Listar histórico de alertas
