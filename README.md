# Análise de Sentimentos no Reddit

## Descrição do Projeto
Este projeto tem como objetivo realizar uma análise de sentimentos em postagens de um subreddit específico, utilizando ferramentas de processamento de linguagem natural (NLP). Os sentimentos detectados (positivo, negativo ou neutro) são visualizados em gráficos, permitindo identificar padrões e tendências de opinião dentro da comunidade.

## Funcionalidades
- Coleta de postagens de subreddits usando a API do Reddit.
- Pré-processamento de texto para limpeza e tokenização.
- Classificação de sentimentos usando `TextBlob`.
- Geração de gráficos para visualização dos resultados.

## Tecnologias Utilizadas
- Linguagem: **Python**
- Bibliotecas:
  - [`praw`](https://praw.readthedocs.io/) - Para acesso à API do Reddit.
  - [`TextBlob`](https://textblob.readthedocs.io/) - Para análise de sentimentos.
  - [`Matplotlib`](https://matplotlib.org/) e [`Seaborn`](https://seaborn.pydata.org/) - Para visualização de dados.
  - [`Pandas`](https://pandas.pydata.org/) - Para manipulação de dados.

## Pré-requisitos
1. Python 3.8 ou superior instalado.
2. Conta no Reddit com permissões para criar um aplicativo.
3. Bibliotecas instaladas com o comando:
   ```bash
   pip install praw textblob pandas matplotlib seaborn