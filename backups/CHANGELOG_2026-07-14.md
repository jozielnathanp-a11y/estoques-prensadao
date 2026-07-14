# Changelog — 14/07/2026

## Atualizações do dia

### 1. Categorias reduzidas para 5
- Removidas: CARNES, CONGELADOS, RESFRIADOS, QUEIJOS, SECOS, VERDURAS, Pães, Temperos
- Mantidas: Bebidas, Bruto, Processado, Embalagens, Limpeza
- Aplicado em: Centro, Delivery, Boqueirão, CD, Chefão (cadastro + filtro)

### 2. Aba de Descarte (NOVO)
- Nova aba 🗑️ DESCARTE em todos os painéis (Centro, Delivery, Boqueirão, CD, Chefão)
- Funcionalidades:
  - Seleção de produto + quantidade + motivo (Vencido, Estragado, Queimou, Erro de produção, Outro)
  - Desconto automático do estoque da unidade ao registrar
  - Registro de movimentação tipo "descarte" no banco (com horário, produto, qtd, motivo)
  - Aparece no relatório/extrato em coluna própria ao lado da contagem do dia
  - No Chefão: aparece no Histórico Geral (com filtro dedicado) e na aba Entradas
  - Ícone 🗑️ na cor roxa, motivo exibido junto

### 3. Chefão — Relatório de Descarte
- Histórico Geral: filtro "Descartes" adicionado ao select de tipos
- Cores e ícones do descarte configurados (🗑️ roxo)
- Motivo do descarte exibido em cada item do histórico
- Aba Entradas: descartes aparecem agrupados no final, por unidade

### Commits do dia (20 commits)
- e46750d a 2b5bd42

### Painéis atualizados
- centro.html
- delivery.html  
- boqueiraw.html
- cd.html
- matriz.html (Chefão)
