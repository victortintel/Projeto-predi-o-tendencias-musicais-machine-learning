# 🎵 Marketing Analytics: Previsão de Tendências Musicais nas Redes Sociais

Este projeto foi desenvolvido com o objetivo de aplicar técnicas de **Data Science e Machine Learning** na análise de músicas que viralizam nas redes sociais, em especial no TikTok. Utilizamos um conjunto de dados robusto com as faixas mais transmitidas no Spotify em 2024, além de métricas de engajamento em outras plataformas como YouTube, Deezer, SoundCloud, Shazam, entre outras.

---

## 🧠 Objetivo do Projeto

- Criar um modelo preditivo de Machine Learning que identifique se uma música tem potencial de viralizar.
- Responder perguntas estratégicas para marketing musical.
- Analisar variáveis mais relevantes para o sucesso de uma faixa nas redes sociais.
- Usar o projeto como estudo de caso de Marketing Analytics aplicado à indústria fonográfica.

---

## 📊 Dataset

**Fonte de dados:** [Kaggle - Most Streamed Spotify Songs 2024](https://www.kaggle.com/datasets/nelgiriyewithana/most-streamed-spotify-songs-2024)

O dataset inclui:

- Nome da música e artista
- Número de streams no Spotify, YouTube, SoundCloud e Pandora
- Métricas de playlists (alcance, quantidade)
- Engajamento em TikTok (posts, views, likes)
- Métricas adicionais: Shazam, Apple Music, TIDAL, Amazon Music, etc.

---

## 🔎 Perguntas de Negócio Respondidas

1. **Qual artista possui mais músicas na plataforma?**
2. **Quais são as 20 músicas com maiores tendências?**
3. **Quais os 20 artistas com maior potencial de viralização?**

---

## 🧪 Modelagem e Algoritmos Usados

- **SVM (Support Vector Machine)** — com GridSearch para ajuste de hiperparâmetros
- **SMOTE** — para balanceamento das classes (oversampling)
- **StandardScaler** — para normalização dos dados
- **LabelEncoder** — para tratamento de variáveis categóricas

---

## 📈 Métricas de Avaliação

- Curva ROC
- AUC (Área sob a curva)
- Matriz de Confusão
- Accuracy
- Classification Report (Precision, Recall, F1-Score)

---

## 🔬 Principais Ferramentas Utilizadas

- **Python**
- **Pandas, Numpy**
- **Seaborn, Matplotlib, Plotly**
- **Scikit-learn**
- **Imbalanced-learn**

---

## 📊 Visualizações

- Gráficos de distribuição de popularidade por plataforma
- Correlações entre curtidas, views e viralização
- Comparação entre artistas mais populares vs mais virais

---

## 📌 Conclusões

- Métricas de engajamento no TikTok e playlists do Spotify são os principais preditores de viralização.
- O modelo SVM apresentou bom desempenho com ROC AUC relevante.
- Projetos de Marketing Analytics podem ser aplicados em diversas indústrias, incluindo a musical.




