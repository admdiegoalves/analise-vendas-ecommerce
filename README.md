# 🛒 Análise de Desempenho de Lojas — Recomendação Estratégica de Desinvestimento

Análise exploratória de dados de vendas de uma rede de e-commerce com 4 unidades, com o objetivo de identificar a loja de menor desempenho e embasar uma decisão estratégica de desinvestimento.

---

## 🎯 Problema de Negócio

Uma rede de e-commerce com quatro lojas busca otimizar seu portfólio de ativos. A questão central:

> **Qual unidade apresenta o pior desempenho e deve ser priorizada para venda?**

A recomendação final é baseada em análise quantitativa de KPIs de receita, satisfação do cliente e eficiência logística.

---

## 📊 KPIs Analisados

| Métrica | Descrição |
|---|---|
| Faturamento Total | Contribuição de receita por loja |
| Avaliação Média dos Clientes | Satisfação e qualidade percebida (1–5) |
| Frete Médio | Eficiência logística e custo operacional |
| Distribuição Geográfica | Mapeamento de densidade de clientes por região |

---

## 🔍 Principais Resultados

- **Loja 4** apresenta o menor faturamento total entre as quatro unidades
- **Loja 4** registra uma das menores médias de avaliação de clientes, indicando risco de churn e insatisfação
- A combinação de baixa receita + baixa satisfação configura o pior perfil de risco-retorno do portfólio

**Recomendação:** Desinvestir na Loja 4, direcionando o capital para expansão das unidades de maior performance.

---

## 🛠️ Stack Técnica

- **Python** — Pandas, Matplotlib, Seaborn
- **Jupyter Notebook / Google Colab**
- **Análise Exploratória de Dados (EDA)**
- **Visualização de dados para suporte à decisão**

---

## 📁 Estrutura do Projeto

```
analise-vendas-ecommerce/
├── analise_lojas.ipynb   # Notebook com EDA completa e recomendação
└── README.md
```

---

## ▶️ Como Executar

1. Abra o notebook `analise_lojas.ipynb` no Google Colab ou Jupyter
2. Execute todas as células em sequência
3. Os dados são carregados diretamente via URL — sem necessidade de download manual

---

## 📌 Aprendizados e Aplicações

Este projeto simula um cenário real de **analytics para suporte à decisão estratégica**, comum em áreas de:
- Business Intelligence
- Customer Analytics
- Revenue Operations

A mesma abordagem pode ser aplicada a análises de churn, ranking de produtos, segmentação de clientes e avaliação de performance de equipes.

---

*Desenvolvido por [Diego Alves](https://www.linkedin.com/in/admdiegoalves/)*
