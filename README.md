# 📊 BF LUBS — Análise Exploratória de Vendas (2018–2024)

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-EDA-lightblue?logo=pandas)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualizations-orange)
![Seaborn](https://img.shields.io/badge/Seaborn-Plots-teal)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)

## 📌 Contexto

A **BF LUBS** é uma empresa fictícia especializada na produção e distribuição de lubrificantes industriais, com atuação em múltiplas regiões do Brasil e atendimento a setores como Energia e Químicos, Ciências e Saúde e Manufatura.

Entre 2018 e 2024, a empresa registrou uma **queda expressiva no volume de vendas**. Este projeto conduz uma Análise Exploratória de Dados (EDA) completa sobre o histórico comercial da empresa, com o objetivo de entender **onde, como e por que** essa deterioração ocorreu.

---

## ❓ Perguntas de Negócio

1. O volume de vendas está caindo? Se sim, desde quando e com qual intensidade?
2. A queda de volume está impactando a receita da empresa?
3. Quais produtos são os maiores responsáveis pela queda?
4. A queda está concentrada em algum mercado específico ou é generalizada?
5. Há alguma região ou estado onde o problema é mais grave?
6. Quais perfis de clientes (por volume de compra) estão sendo mais perdidos?
7. A empresa está perdendo clientes, ou os clientes existentes estão comprando menos — ou ambos?
8. Existem registros atípicos na base que possam estar distorcendo a análise?
9. Quais segmentos concentram a maior parte da queda acumulada?

---

## 🗂️ Estrutura do Projeto

```
📦 bf-lubs-sales-eda
 ┣ 📓 BF_LUBS_Sales_Portfolio.ipynb   # Notebook principal com a análise completa
 ┣ 📄 README.md
 ┗ 📁 data/
    ┗ BF_LUBS_Sales.rar (A base de dados teve de ser compactada.)              # Base de dados utilizada
```

---

## 🔍 Etapas da Análise

| # | Etapa | Descrição |
|---|---|---|
| 1 | Configuração do Ambiente | Importação de bibliotecas e configurações |
| 2 | Carregamento e Inspeção | Estrutura, tipos de dados e qualidade |
| 3 | Tendências Temporais | Volume, receita, clientes ativos e preço médio |
| 4 | Análise por Produto | Identificação do produto mais impactado |
| 5 | Análise por Mercado | Comportamento por setor industrial |
| 6 | Análise Geográfica | Padrões por região e estado |
| 7 | Segmentação de Clientes | Faixas de volume: Baixo, Médio, Alto e Muito Alto |
| 8 | Tratamento de Outliers | Método IQR + conhecimento de domínio |
| 9 | Comparação 2018 vs 2024 | Variação de volume médio por segmento |
| 10 | Visualização dos Impactos | Diferença por região, mercado e faixa |
| 11 | Análise de Pareto | Top 15 segmentos com maior queda acumulada |

---

## 📈 Principais Achados

- 📉 **Queda contínua de volume** de 2018 a 2024, com colapsos em 2020 e 2022
- 💰 **Receita sustentada artificialmente** pelo aumento do preço médio
- 🧴 **Lubs1** é o produto central da queda — domina o volume e lidera o declínio
- 🏭 **Energia e Químicos**, **Ciências e Saúde** e **Manufatura** concentram as maiores perdas por mercado
- 🗺️ A queda é **homogênea geograficamente** — nenhuma região ou estado isolado explica o problema
- 👥 Clientes da faixa **"Muito Alto"** (>900 L/mês) perderam volume e quantidade simultaneamente — o cenário mais crítico
- 🎯 O **Pareto** confirma que poucos segmentos explicam ~80% da queda total

---

## 🛠️ Tecnologias Utilizadas

- **Python 3.x**
- **Pandas** — manipulação e análise de dados
- **Matplotlib** — visualizações gráficas
- **Seaborn** — estilização de gráficos
- **Jupyter Notebook** — ambiente de desenvolvimento

---

## ▶️ Como Executar

```bash
# Clone o repositório
git clone https://github.com/seu-usuario/bf-lubs-sales-eda.git

# Acesse a pasta
cd bf-lubs-sales-eda

# Instale as dependências
pip install pandas matplotlib seaborn jupyter

# Abra o notebook
jupyter notebook BF_LUBS_Sales_Portfolio.ipynb
```

---

## 👤 Autor

Feito por **[Leonardo Pacheco Pereira]** · [LinkedIn](https://linkedin.com/in/leonardo-pacheco-pereiraabc) · [GitHub](https://github.com/Leopachecop)
