# Desafio Dados & BI – Power BI

## 📌 Objetivo do Projeto
Este projeto tem como objetivo demonstrar habilidades em análise de dados e
Business Intelligence utilizando o Power BI, com foco em performance comercial,
rentabilidade, descontos e lucratividade.

O desafio também avalia boas práticas de versionamento de projetos de BI por
meio do formato **Power BI Project (.pbip)**.

---

## 🛠️ Decisões Técnicas
- O projeto foi desenvolvido utilizando o formato **.pbip**, permitindo o
  versionamento separado do modelo semântico (Dataset) e do relatório (Report).
- O versionamento foi realizado via **Git/GitHub**, com repositório público.
- A modelagem adotada segue o padrão **Star Schema (Esquema Estrela)**,
  visando melhor performance, simplicidade e escalabilidade.
- Medidas foram centralizadas no modelo semântico para reutilização e
  padronização das métricas.

---

## 🧱 Modelagem de Dados
O modelo de dados foi estruturado em esquema estrela, composto por:

- **Tabela Fato**: Vendas
- **Tabelas Dimensão**:
  - Clientes
  - Produtos
  - Categoria / Subcategoria
  - Região
  - Data

Essa abordagem facilita análises temporais, comparativos e segmentações
de performance.

---

## 📐 Dicionário de Medidas (DAX)

| Medida | Descrição |
|------|-----------|
| Faturamento | Soma do valor total das vendas |
| Profit | Lucro líquido após descontos |
| Margem (%) | Percentual de lucro sobre o faturamento |
| Desconto Médio | Média de desconto aplicado nas vendas |
| Crescimento YoY (%) | Comparativo percentual de lucro entre o ano atual e o ano anterior |

---

## 📊 Insights de Negócio
- Subcategorias com alto faturamento nem sempre apresentam maior lucratividade.
- Níveis elevados de desconto impactam negativamente a margem em determinados
  produtos e categorias.
- Alguns clientes concentram grande volume de vendas, porém com baixa
  rentabilidade.
- Existem diferenças relevantes de performance entre categorias e regiões,
  indicando oportunidades de otimização comercial.

---

## 🚀 Considerações Finais
O projeto permite uma visão analítica clara sobre performance comercial e
rentabilidade, auxiliando a tomada de decisão estratégica baseada em dados.

A estrutura do projeto segue boas práticas de BI e versionamento, garantindo
organização, escalabilidade e facilidade de manutenção.
