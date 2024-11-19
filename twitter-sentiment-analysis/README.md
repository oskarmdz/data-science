# Twitter Sentiment Analysis

## Descripción

Este proyecto utiliza la API de Twitter (a través de la biblioteca `tweepy`) para obtener tweets recientes con un término de búsqueda específico. Luego, analiza los sentimientos de estos tweets usando un modelo de procesamiento de lenguaje natural (PLN) proporcionado por la librería `transformers` de Hugging Face. Los resultados son almacenados en una base de datos MySQL para su posterior análisis.

## Funcionalidades

1. **Recuperación de Tweets**: Obtiene los tweets más recientes que contienen un término de búsqueda específico.
2. **Almacenamiento en Base de Datos**: Guarda los tweets extraídos en una base de datos MySQL.
3. **Análisis de Sentimientos**: Realiza un análisis de sentimientos en los tweets usando un modelo preentrenado.
4. **Impresión de Resultados**: Muestra los resultados en consola, tanto los primeros tweets como los resultados del análisis de sentimientos.

## Requisitos

Antes de ejecutar el proyecto, asegúrate de tener los siguientes requisitos:

- **Python 3.6+**
- **Bibliotecas de Python**:
  - `tweepy`: Para interactuar con la API de Twitter.
  - `pandas`: Para manipulación de datos.
  - `mysql-connector-python`: Para interactuar con la base de datos MySQL.
  - `transformers`: Para realizar el análisis de sentimientos.

Instala las dependencias necesarias ejecutando el siguiente comando:

```bash
pip install tweepy pandas mysql-connector-python transformers
