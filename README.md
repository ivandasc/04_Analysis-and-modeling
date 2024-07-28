# Análise de Dados sobre Ética em IA

## Enunciado
Você foi contratado por uma empresa de consultoria para realizar uma análise dos dados sobre ética em Inteligência Artificial (IA) usando o conjunto de dados fornecido. Seu objetivo é extrair insights relevantes que possam ajudar os clientes a entender as tendências, os principais temas e as preocupações relacionadas à ética em IA com base nos artigos disponíveis.

## Problemas a Serem Solucionados

### Análise Exploratória de Dados (AED)
- Realizar uma AED para entender a estrutura e as características do conjunto de dados.

### Identificação de Tendências
- Identificar as tendências ao longo do tempo em relação aos temas discutidos nos artigos sobre ética em IA.

### Principais Tópicos
- Identificar os principais tópicos discutidos nos artigos e sua relevância.

### Análise de Sentimento
- Realizar uma análise de sentimento para entender a percepção geral em relação à ética em IA.

### Visualização de Dados
- Criar visualizações informativas para comunicar os insights obtidos de forma clara e eficaz.

## Estrutura do Projeto

/src

eda.py # Script para Análise Exploratória de Dados (AED)
trend_analysis.py # Script para Identificação de Tendências
topic_modeling.py # Script para Identificação dos Principais Tópicos
sentiment_analysis.py # Script para Análise de Sentimento
data_visualization.py # Script para Visualização de Dados
/data
ethics_in_ai_data.csv # Conjunto de dados sobre ética em IA
/notebooks
EDA.ipynb # Notebook para Análise Exploratória de Dados
Trend_Analysis.ipynb # Notebook para Identificação de Tendências
Topic_Modeling.ipynb # Notebook para Identificação dos Principais Tópicos
Sentiment_Analysis.ipynb # Notebook para Análise de Sentimento
Data_Visualization.ipynb # Notebook para Visualização de Dados
/docs
report.md # Relatório detalhado do projeto
/README.md # Documentação do projeto
/requirements.txt # Dependências do projeto

## Como Usar

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/ethics-in-ai-analysis.git
   cd ethics-in-ai-analysis
2. Instale as dependências:
!pip install -r requirements.txt
3.Execute a Análise Exploratória de Dados (AED):
python src/eda.py
4. Identifique as Tendências nos dados:
   python src/trend_analysis.py
5. Identifique os Principais Tópicos:
   python src/topic_modeling.py
6. Realize a Análise de Sentimento:
   python src/sentiment_analysis.py
7. Crie as Visualizações de Dados:
   python src/data_visualization.py

### Resultados
Os resultados da análise e modelagem serão apresentados em forma de gráficos e tabelas, disponíveis nos notebooks na pasta /notebooks e no relatório detalhado em /docs/report.md.

### Conclusões
As conclusões serão baseadas nos insights obtidos a partir da análise exploratória de dados, identificação de tendências, modelagem de tópicos e análise de sentimento. O objetivo é fornecer recomendações que ajudem os clientes a entender melhor as preocupações e os temas emergentes relacionados à ética em IA.
