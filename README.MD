# Projeto 02 – Análise de Distribuição e Preço Médio de Cafés com Python

## Descrição
Este projeto tem como objetivo aprofundar a análise exploratória de dados de vendas de café, com foco na **distribuição de preços**, **avaliações dos consumidores** e **identificação de padrões relevantes**.  
A análise foi realizada utilizando **Python**, **Pandas** e **Seaborn**, com visualizações estatísticas para apoio à tomada de decisão.

---

## Objetivos
- Analisar a distribuição de preços dos cafés;
- Identificar outliers e variações de preço;
- Avaliar a relação entre preço e avaliação dos produtos;
- Comparar os cafés mais caros e os mais bem avaliados;
- Aplicar boas práticas de visualização de dados.

---

## Tecnologias Utilizadas
- Python
- Pandas
- Seaborn
- Matplotlib
- Jupyter Notebook (.ipynb)

---

## Estrutura do Projeto
Projeto_02_Analise_Distribuicao_Preco_Medio_Cafe/
│
├── projeto_02_analise_distribuicao_preco_medio_cafe.ipynb
├── coffee-walmart-stores.csv
└── README.md

---

## Etapas da Análise
1. Importação e leitura do conjunto de dados;
2. Análise inicial da estrutura dos dados;
3. Tratamento de valores nulos;
4. Análise da distribuição de preços e avaliações;
5. Cálculo do preço médio e mediano dos cafés;
6. Seleção dos cafés com maior relevância analítica;
7. Criação de visualizações estatísticas com Seaborn.

---

## Principais Análises Realizadas
- Boxplot da distribuição de preços dos cafés;
- Boxplot das avaliações por tipo de café;
- Filtragem dos **6 tipos de café com maior mediana de preço**;
- Filtragem dos **6 tipos de café com maior média de avaliação**;
- Análise do preço médio e mediano por categoria;
- Visualização da distribuição de preços e avaliações utilizando distplot.

---

## Decisões Analíticas
- Optou-se pelo uso da **mediana do preço** em vez da soma, devido à presença de outliers, garantindo uma representação mais fiel do valor típico dos produtos;
- A filtragem dos Top 6 cafés foi aplicada para reduzir ruído visual e melhorar a interpretação dos gráficos;
- As análises foram orientadas para responder perguntas de negócio relacionadas à percepção de valor dos consumidores.

---

## Resultados
- Identificação de cafés premium com preços elevados;
- Verificação de que cafés mais bem avaliados nem sempre são os mais caros;
- Compreensão mais clara da distribuição de preços e avaliações no mercado analisado.

---

## Próximos Passos
- Comparar diretamente preço médio e avaliação média;
- Integrar análises com Power BI;
- Aplicar análises complementares utilizando SQL.

---

## Autor
**Felipe Sousa**  
Formado em Ciências da Computação (2024)  
Estudante de Cientista de Dados – Python e SQL