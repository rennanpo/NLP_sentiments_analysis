# Análise de Sentimentos com LSTM e RNN

Este projeto compara o desempenho de modelos de redes neurais recorrentes (RNN e LSTM) na tarefa de análise de sentimentos usando o dataset IMDB.

## 📌 Objetivos

- Comparar a acurácia e o tempo de treino entre modelos RNN e LSTM
- Analisar casos divergentes entre as previsões dos modelos
- Avaliar o impacto de dois hiperparâmetros no desempenho da LSTM:
  - Número de unidades na camada LSTM
  - Tamanho do vocabulário (número de palavras consideradas)

## 🧪 Experimentos

Experimentos com variação de hiperparâmetros mostram que:
- Menor número de unidades (64) teve melhor desempenho
- Vocabulário de 5000 palavras teve a maior acurácia (0.8495)

## 📊 Visualizações

Foi gerado um heatmap que mostra a relação entre número de unidades, vocabulário e acurácia.

## 📁 Estrutura

- `main.ipynb`: Notebook principal com todo o código de treino e avaliação
- `requirements.txt`: Dependências do projeto
- `README.md`: Este arquivo

## ▶️ Execução

```bash
pip install -r requirements.txt
