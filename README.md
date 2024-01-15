# Sistema de Gerenciamento de Estoque

- Baseado na conversa entre o desenvolvedor e o especialista de domínio, podemos identificar as seguintes entidades de domínio e casos de uso para o sistema de gerenciamento de estoque:

## Entidades de Domínio

1. **Produto**
   - Entidade central do sistema.
   - Atributos: número de identificação único, tamanho, cor, etc.

2. **Estoque**
   - Representa a quantidade disponível de cada produto.

3. **Alerta de Estoque**
   - Alertas gerados quando o estoque de um produto atinge um nível mínimo definido.

4. **Histórico de Vendas**
   - Registros de todas as vendas realizadas.
   - Inclui quantidade vendida, lucros gerados, e tendências de vendas.

5. **Ordem de Compra**
   - Representa as compras realizadas para reabastecer o estoque.

6. **Fornecedor**
   - Entidades que fornecem os produtos.
   - Possibilidade de integração com o sistema para atualizações sobre entregas.

## Casos de Uso (Ações)

1. **Rastrear Produtos Individualmente**
   - Atribuir um número de identificação único a cada produto.
   - Adicionar informações extras para rastreio.

2. **Definir Quantidades Mínimas de Estoque**
   - Estabelecer um limite mínimo para cada produto.
   - Gerar alertas quando o estoque estiver próximo de esgotar.

3. **Receber Alertas de Estoque**
   - Enviar notificações por e-mail e no sistema quando o estoque estiver baixo.

4. **Visualizar Histórico de Vendas e Estoque**
   - Consultar dados de vendas passadas.
   - Análise de lucros por produto e tendências de estoque.

5. **Gerenciar Ordens de Compra**
   - Criar e administrar ordens de compra com base nas quantidades mínimas de estoque e tendências de vendas.

6. **Integração com Fornecedores**
   - Integrar o sistema com os fornecedores para atualizações sobre prazos de entrega.
