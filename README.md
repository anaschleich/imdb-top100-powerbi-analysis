# 🎬 IMDb Top 100 Movies - Análise Interativa no Power BI

## 📌 Sobre o Projeto

Dashboard interativo desenvolvido em Power BI para análise dos 100 filmes mais bem avaliados do IMDb em 2025. O projeto explora tendências cinematográficas, desempenho de diretores, distribuição de gêneros e a relação entre avaliações críticas e sucesso comercial.

## 🎯 Objetivos

- Identificar padrões nos filmes mais bem avaliados
- Analisar a performance de diretores e gêneros cinematográficos
- Comparar avaliações do IMDb com Rotten Tomatoes
- Visualizar a evolução temporal da produção cinematográfica

## 📊 Principais Insights

- **100 filmes analisados** com rating médio de **8.39/10**
- **Drama** é o gênero dominante (21.05% do total)
- **Stanley Kubrick** lidera como diretor com maior rating médio
- Faturamento total de **167 bilhões USD**
- Rating médio no Rotten Tomatoes: **92.67%**

## 🛠️ Ferramentas Utilizadas

- **Power BI Desktop** - Desenvolvimento do dashboard
- **DAX** - Criação de métricas calculadas
- **Power Query** - Tratamento e transformação de dados

## 📈 Visualizações

### Dashboard Completo
<img width="1422" height="786" alt="screenshot-dash-imdb" src="https://github.com/user-attachments/assets/ad42fcd4-ab31-47f4-96c0-df6929e1b489" />


### Principais Gráficos
- **Top 10 filmes por rating IMDb** - Gráfico de barras horizontal
- **Distribuição de gêneros** - Gráfico de rosca
- **Top 10 filmes no Rotten Tomatoes** - Ranking por rating em %
- **Filmes por ano** - Linha temporal
- **Rating vs Box Office** - Scatter plot
- **Distribuição de ratings** - Histograma

## 📁 Estrutura do Projeto

- `imdb_analysis.pbix` - Arquivo Power BI
- `data/` - Dataset utilizado

## 🔍 Metodologia

1. **Coleta de dados:** Dataset do Kaggle com informações de 100 filmes
2. **Tratamento:** Limpeza e padronização no Power Query
3. **Modelagem:** Criação de relacionamentos e métricas DAX
4. **Visualização:** Design de dashboard focado em UX/UI
5. **Análise:** Extração de insights e padrões

## 📌 KPIs Principais
```DAX
Average IMDB Rating = AVERAGE('IMDB_top_100_movies'[IMDb Rating(0-10)])
Total Gross (USD) = SUM('IMDB_top_100_movies'[Box Office ($M)])* 1000000
Total Movies = COUNTROWS('IMDB_top_100_movies')
```

## 🚀 Como Usar

1. Baixe o arquivo `.pbix`
2. Abra no Power BI Desktop
3. Explore os filtros interativos
4. Analise os diferentes painéis

## 📊 Fonte dos Dados

Dataset: [IMDb Top 100 Movies Dataset 2025 Edition](https://www.kaggle.com/datasets/shayanzk/imdb-top-100-movies-dataset-2025-edition)

## 👨‍💻 Autora

**Ana Luíza Righi Schleich**
- LinkedIn: (https://www.linkedin.com/in/anaschleich)
- Email: anaschleich@yahoo.com.br



⭐ Se este projeto foi útil, deixe uma estrela!
```
