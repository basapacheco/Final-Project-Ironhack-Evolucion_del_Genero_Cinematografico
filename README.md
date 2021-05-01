# EVOLUCIÓN DEL GENERO CINEMATOGRAFICO (:film_projector: :file_cabinet:)


IMAGEN DISNEY, NETFLIX, AMAZON PRIME, HULU y IMDB


El proyecto presentado es un estudio de la evolución del genero cinematográfico en las plataformas de Disney, Netflix, Amazon Prime y Hulu, con una unión de sus valoraciones de IMDB. Este estudio pretende desvelar como a evolucionado la industria del contenido cinematográfico para adaptarse al consumidor.

Los datos utilizados en este proyecto se han sacado de varias fuentes de datos de Kaggle y más tarde han sido tratados con el fin de estandarizarlos y rellenar las partes faltantes.

Este proceso ha dado como resultado dos archivos de información mediante un análisis de la evolución del contenido y un análisis de regresión, donde podremos apreciar como la industria esta creciendo en cantidad y calidad para poder satisfacer todo tipo de demanda, y como ha ido creciendo la industria en términos de cantidad para poder dar respuesta a la alta demanda en las plataformas de streaming.


### Datos

El dataset de este proyecto proviene de un match entre varios dataset de Kaggle y un posterior proceso de limpieza y unión de datos, dando como resultado los datos ubicados en la carpeta Data los cuales se han pasado a denominar coste_año.csv, disney_plus.csv, netflix_titles.csv y peliculas_plataforma.csv 

Dichos datos son producto de la recolección, análisis y limpiezas de las siguientes fuentes.

-Datos 1: https://www.kaggle.com/shivamb/netflix-shows
-Datos 2: https://www.kaggle.com/chasewillden/netflix-shows
-Datos 3: https://www.kaggle.com/nishanthkv/netflix
-Datos 4: https://www.kaggle.com/harshitshankhdhar/netflix-and-amazon-prime-tv-series-dataset
-Datos 5: https://www.kaggle.com/ruchi798/movies-on-netflix-prime-video-hulu-and-disney
-Datos 6: https://www.kaggle.com/prateekmaj21/disney-movies
-Datos 7: https://www.kaggle.com/unanimad/disney-plus-shows
-Datos 8: https://www.kaggle.com/nilimajauhari/amazon-prime-tv-shows


### LIBRERÍAS USADAS

-Libreria 1 PANDAS
-Libreria 2 MATPLOTLIB
-Libreria 3 SEABORN

## Data Preparation :chart_with_upwards_trend: :gear:

1. Descarga de datos de distintas plataformas en Kaggle
2. Estandarizar datos por parámetros simétricos
3. Limpieza manual de datos mediante Tableu:
	2.1 Rellenar datos nulos
	2.2 Fusionar Tabla
	2.3 Descarga de datasets
	2.4 Limpieza de datos y agregación de nulos faltantes
3. Resultado final, 4 dataset:
	-Peliculas_plataforma.csv
	-Coste_año.csv
	-Disney_plus.csv
	-Netflix_titles.csv


## Data Analysis :chart_with_downwards_trend: :mag:

### Overview

Se han creado dos análisis, un análisis de la evolución del cine en plataformas y un análisis de regresión.

Análisis de la evolución del cine en plataformas

Este análisis comprende un análisis exploratorio del contenido junto a dos gráficas, una gráfica para entender como a evolucionado la industria en niveles de calidad y un análisis que nos premie ver como evoluciona la cantidad de contenido ofrecido.

Análisis de Regresión
Este análisis nos permite ver cómo se ha ido creciendo el contenido a los largo del tiempo y, finalmente, ver el contenido más demandado y valorado.



## Proximos pasos :chart_with_downwards_trend: :mag:
1. Crear Api de recolección de automaticas datos en NETFLIX, DISNEY, HULU 
2. Crear Api de recolección de datos de IMDB
2. Crear Dashboard de recomendación
