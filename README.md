# Mapeando-o-dom-nio
# Análise de Domínio - Sistema de Gerenciamento de Estoque

## 🧩 Entidades de Domínio

- **Produto**
  - ID único, nome, tamanho, cor, quantidade em estoque, quantidade mínima, preço de venda, custo de aquisição.
- **Estoque**
  - Movimentações de entrada e saída, data, tipo de movimentação (venda, compra, ajuste).
- **Venda**
  - Data da venda, produto vendido, quantidade, valor, lucro gerado.
- **Ordem de Compra**
  - Produtos incluídos, quantidades, status da ordem (pendente, enviado, entregue), fornecedor associado.
- **Fornecedor**
  - Nome, contato, prazo de entrega, produtos fornecidos.
- **Usuário**
  - Nome, e-mail (para notificação), preferências de alerta.
- **Alerta**
  - Produto relacionado, tipo (estoque baixo), método de envio (e-mail, sistema), data/hora.

## ✅ Casos de Uso (Funcionalidades)

1. Cadastrar/Editar/Remover Produto  
2. Registrar Movimentações de Estoque (entrada, saída, ajuste)  
3. Definir e atualizar quantidade mínima de estoque por produto  
4. Emitir alerta quando o estoque estiver abaixo do mínimo  
5. Enviar alertas por e-mail e/ou notificação no sistema  
6. Visualizar histórico de vendas por período  
7. Visualizar lucro por produto  
8. Listar produtos mais vendidos por período  
9. Analisar tendências de estoque ao longo do tempo  
10. Gerar ordens de compra automaticamente com base em regras  
11. Cadastrar e gerenciar fornecedores  
12. Receber atualizações automáticas de prazos de entrega  
13. Gerenciar usuários e suas preferências de notificação  
