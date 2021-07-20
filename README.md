# Actividad Integradora 2

## Descripción
El presente proyecto consiste principalmente de un analizador de sentimientos para tweets de Tweeter, tweets especificos de un usuario, y *text-to-speech*. Además se incluyeron fucionalidades adicionales que son descritas más adelante.

## Cómo ejecutar el código
Necesitaras acceder al archivo *Integrador_2.ipynb* en Google Colab, y tener credenciales para utilizar las APIs de twitter, youtube y reddit.
Además deberás instalar los paquetes de *requirement.txt*

## Funcionalidades adicionales


### Analisis de sentimientos de comentarios de Youtube
Obtiene los comentarios de un video en particular de Youtube con la [API de Google](https://console.cloud.google.com/marketplace/product/google/youtube.googleapis.com?q=search&referrer=search&project=sentiment-comments&supportedpurview=project) y realiza un análisis de sentimientos sobre dichos comentarios, clasificandolos como positivos o negativos.

### Clasificación múltiple de textos

Para esta funcionalidad se llevó a cabo word embedding con [GloVe](https://www.kaggle.com/danielwillgeorge/glove6b100dtxt?select=glove.6B.100d.txt) y se desarrolló un modelo con LSTM usando keras. El objetivo del modelo es clasificar y predecir los diferentes tipos de etiquetas que se identifican en un comentario. 

Para el modelo se utilizó una [base de datos](https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge/overview) con comentarios tóxicos recabados de Wikipedia y etiquetados según el tipo de toxicidad identificado.

### FUNCIONALIDAD 3
En este notebook se busca predecir si una pelicula tiene un review positivo o negativo basado en sentimientos utilizando regresión logistica y Naive Bayes Model comparado con una maquina de vectores. Y de esto generar las palabras mas utilizadas en cada tipo de review para tener una prediccion mas adecuada. Este analisis de sentimiento esta basado en una base de datos de IMDB. (https://www.kaggle.com/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)

### Recursos / Bases de datos utilizados
 - [Tutorial Sentiment Analyzer](https://www.youtube.com/playlist?list=PLQVvvaa0QuDf2JswnfiGkliBInZnIC4HL)
- [Dataset con reviews positivas y negativas](https://pythonprogramming.net/static/downloads/short_reviews/)
- [Base de datos con tweets positivos, negativos y neutrales](https://www.kaggle.com/kazanova/sentiment140)

## Integrantes
  - Víctor Villarreal. 
  - Gerardo Silva
  - Juan Donaldo 
  - Ricardo Ramirez
