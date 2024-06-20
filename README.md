# Estudio de la Evolución del Género Cinematográfico

Este repositorio contiene dos proyectos centrados en el estudio de la evolución del género cinematográfico. El primer proyecto es el Trabajo de Fin de Máster (TFM) presentado en el curso de Ironhack de Data Analytics. El segundo proyecto es un estudio adicional realizado posteriormente.

## Estructura del Repositorio

- **TFM (Trabajo de Fin de Máster)**: Estudio de la evolución del género cinematográfico en plataformas de streaming.
- **Estudio-del-Genero-Cinematografico**: Estudio del género cinematográfico centrado en la producción a nivel mundial.

----


## TFM: EVOLUCIÓN DEL GÉNERO CINEMATOGRÁFICO EN PLATAFORMAS DE STREAMING

### Descripción
El proyecto es un estudio de la evolución del género cinematográfico en las plataformas de Disney, Netflix, Amazon Prime y Hulu, junto con sus valoraciones de IMDB. Este estudio pretende revelar cómo ha evolucionado la industria del contenido cinematográfico para adaptarse al consumidor.

### Objetivos
- Analizar la evolución del contenido cinematográfico en las plataformas de streaming más populares.
- Evaluar la calidad del contenido ofrecido a través de las valoraciones de IMDB.
- Estudiar la cantidad de contenido producido a lo largo del tiempo.

### Datos
Los datos utilizados en este proyecto provienen de varias fuentes de Kaggle y han sido tratados para estandarizarlos y rellenar las partes faltantes. Los archivos resultantes son:

- `coste_año.csv`
- `disney_plus.csv`
- `netflix_titles.csv`
- `peliculas_plataforma.csv`

### Fuentes de Datos
- [Netflix Shows 1](https://www.kaggle.com/shivamb/netflix-shows)
- [Netflix Shows 2](https://www.kaggle.com/chasewillden/netflix-shows)
- [Netflix Data](https://www.kaggle.com/nishanthkv/netflix)
- [Netflix and Amazon Prime TV Series](https://www.kaggle.com/harshitshankhdhar/netflix-and-amazon-prime-tv-series-dataset)
- [Movies on Netflix, Prime Video, Hulu, and Disney+](https://www.kaggle.com/ruchi798/movies-on-netflix-prime-video-hulu-and-disney)
- [Disney Movies](https://www.kaggle.com/prateekmaj21/disney-movies)
- [Disney Plus Shows](https://www.kaggle.com/unanimad/disney-plus-shows)
- [Amazon Prime TV Shows](https://www.kaggle.com/nilimajauhari/amazon-prime-tv-shows)

### Librerías Usadas
- Pandas
- Matplotlib
- Seaborn

### Preparación de Datos 📈 ⚙️
1. **Descarga de datos** de distintas plataformas en Kaggle.
2. **Estandarización de datos** por parámetros simétricos.
3. **Limpieza manual de datos** mediante Tableau:
   - Rellenar datos nulos.
   - Fusionar tablas.
   - Descarga de datasets.
   - Limpieza de datos y agregación de nulos faltantes.
4. **Resultado final**: 4 datasets (`peliculas_plataforma.csv`, `coste_año.csv`, `disney_plus.csv`, `netflix_titles.csv`).

### Análisis de Datos 📉 🔍
1. **Análisis de la evolución del cine en plataformas**:
   - Exploración del contenido.
   - Gráficas sobre la evolución de la industria en términos de calidad y cantidad.
2. **Análisis de Regresión**:
   - Crecimiento del contenido a lo largo del tiempo.
   - Identificación del contenido más demandado y valorado.

---

## Proyecto_Aparte: ESTUDIO DEL GÉNERO CINEMATOGRÁFICO

### Descripción
El proyecto presentado es un estudio de la evolución del género cinematográfico centrándose en la producción en distintos países y su evolución hasta la actualidad. Este proyecto fue presentado al finalizar el curso de Ironhack de Data Analytics.

### Objetivos
- Analizar la evolución de la industria cinematográfica en diferentes países.
- Evaluar el crecimiento de la producción cinematográfica en términos de cantidad y calidad.
- Investigar las tendencias de género cinematográfico en distintas regiones.

### Datos
Los datos utilizados en este proyecto provienen del dataset IMDb movies extensive dataset de Kaggle.

### Fuentes de Datos
- [IMDb Extensive Dataset](https://www.kaggle.com/stefanoleone992/imdb-extensive-dataset)

### Librerías Usadas
- Pandas
- Matplotlib
- Seaborn
- Collections
- mpl_toolkits
- Numpy
- SQLite3
- Mlxtend

### Preparación de Datos 📈 ⚙️
1. **Descarga y limpieza de datos**:
   - Tratamiento de datos nulos.
   - Estandarización de formatos.
   - Fusión de datasets relacionados.

### Análisis de Datos 📉 🔍
1. **Análisis de la evolución de la industria cinematográfica en distintos países**:
   - Estudio de la cantidad de películas producidas por país.
   - Evaluación de la calidad del contenido mediante métricas y valoraciones.
2. **Evaluación del crecimiento en términos de cantidad y calidad**:
   - Análisis temporal del crecimiento de la industria.
   - Identificación de tendencias en géneros cinematográficos.

---

## Instrucciones para Ejecutar los Proyectos

1. Clona este repositorio:
   ```bash
   git clone <URL-del-repo>
   cd <nombre-del-repo>