# Exploración Índice de felicidad y características de audio

## Descripción
Una exploración de datos del índice de felicidad y con datos de características de audio de la API Web de Spotify. 
La intención es hacer el proceso de Ingeniería de características así como un análisis exploratorio que se hace previo
a un algoritmo de aprendizaje automático.

Se juntan datos del *World Happiness Report* con datos de la *API Web de Spotify*.

## Archivos
Se tienen **3 archivos**, cada uno cuenta con su R markdown así como su salida en HTML, se describen a continuación:

- ```obtener-datos.Rmd``` Contiene el código para descargar datos de las dos fuentes mencionadas y resumirlo en un **archivo tidy** localizado en *./data/felicidad-top50.csv*
- ```indFel-TopMusica.Rmd``` Código de análisis exploratorio de datos así como algo de limpieza y reducción de variables.
- ```reporte.Rmd``` Markdown con un reporte de los resultados obtenidos, resumidos.

## Datos

Se generó un archivo en forma tidy con varias características en ```./data/felicidad.top50.csv```, puede reducirse más en base a la aplicación que se desee hacer.
