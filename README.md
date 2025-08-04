# Análise de Dados de Músicas do Spotify

Este notebook realiza uma análise exploratória de um conjunto de dados de músicas do Spotify com base no conjunto de dados de 50 mil músicas - gerado por IA na Kaggle:

````
URL: https://www.kaggle.com/datasets/refiaozturk/spotify-songs-dataset?resource=download
````

### 1. Tratamento de Dados Ausentes

Para garantir a qualidade da análise, os dados ausentes foram tratados da seguinte forma:
- **Duração da Música (`duration`):** Os valores ausentes foram preenchidos com a mediana.
- **Idioma (`language`):** Os valores em branco foram preenchidos com o idioma mais comum (moda).
- **Colaboração (`collaboration`):** Foi criada uma nova coluna `has_collaboration` para indicar se uma música é uma colaboração (`True`) ou não (`False`).

### 2. Análise de Dados Categóricos

Esta análise nos ajuda a entender a composição do conjunto de dados. Os resultados da execução do código mostrarão:
- Os 10 gêneros musicais mais comuns.
- Os 10 artistas com mais músicas no dataset.
- A distribuição de músicas por idioma.
- A distribuição de músicas com e sem conteúdo explícito.
- A distribuição de músicas com e sem colaboração.

### 3. Análise de Dados Numéricos

Esta seção explora as características das variáveis numéricas e suas relações. Serão gerados:
- **Histogramas:** Para visualizar a distribuição da duração, popularidade e streams.
- **Mapa de Calor de Correlação:** Para visualizar a relação linear entre duração, popularidade e streams.

### 4. Análise Temporal (por Ano de Lançamento)

Análise de tendências ao longo dos anos. Serão gerados gráficos para mostrar:
- O número de músicas lançadas por ano.
- A tendência da popularidade média das músicas ao longo dos anos.

--- 
### [DashBoard | Power BI ](/spotify_songs_dashboard.pbix)

### ![DashBoard | Power BI em PDF ](/spotify_songs_dashboard.jpg)
