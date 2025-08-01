# projeto_afinz_wallacelsconceicao
Análise de KPIs de crédito com PostgreSQL (AWS) e Python. Inclui modelagem de dados, criação de view única, queries SQL otimizadas e dashboard executivo com métricas de aprovação, reprovação, faixas de score, bureau, limite concedido, primeira compra e inadimplência inicial (Over 30 Mob 2).

# 📊 Dashboard de KPIs de Crédito – AfinZ (Teste Técnico)

Este projeto implementa a **análise completa do funil de propostas de crédito**, utilizando **PostgreSQL na AWS** com integração em Python (notebook). 

A base foi modelada em um esquema relacional e consolidada em uma **view única** para cálculo de KPIs estratégicos, incluindo:

✅ Total de Propostas (Aprovadas x Reprovadas)  
✅ Efetivados x Abandonados  
✅ Motivos de Reprovação (Ponto de Corte, Política de Crédito, Negativação)  
✅ Distribuição por Faixas de Score (Aprovados e Reprovados)  
✅ Análise de Bureau  
✅ Limite Concedido, Primeira Compra e % Utilização de Limite  
✅ Indicador de Inadimplência: % Over 30 Mob 2 por Ramo  

### 🚀 **Tecnologias Utilizadas**
- **Python (Pandas, Matplotlib, Seaborn)**  
- **PostgreSQL (AWS RDS)**  
- **psycopg2** para conexão com o banco  
- **SQL otimizado** com criação de Views e KPIs  

### 📌 **Objetivo**
Criar um **painel executivo** para monitorar performance de crédito e inadimplência inicial, com cálculos automatizados e gráficos prontos para apresentação.

---

## 🛠️ **Execução**
1. Configurar variáveis de conexão com PostgreSQL no notebook.  
2. Executar o bloco de criação das tabelas e da view `vw_kpi_base`.  
3. Rodar as queries de KPIs e gerar o dashboard final em Python.

---

## 📈 **Resultados**
O notebook gera:
- **Tabela executiva consolidada com todos KPIs**
- **Dashboard visual 3x3 com gráficos de rosca, barras e cartões**
- **Insights estratégicos baseados nos dados**

---

## 📌 **Autor**
Wallace Lima – Projeto de Análise de Crédito e KPIs para AfinZ.
