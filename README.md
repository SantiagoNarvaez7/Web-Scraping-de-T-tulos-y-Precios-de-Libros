# 📚 Análisis de Datos de Libros: Web Scraping y NLP

Este proyecto consiste en un pipeline completo de Ciencia de Datos aplicado al mercado de libros online. A través de técnicas de **Web Scraping** y **Procesamiento de Lenguaje Natural (NLP)**, extraemos información del sitio sandbox *Books to Scrape* para analizar la relación entre el léxico de los títulos y el precio de venta.

## 🚀 Abrir en Google Colab

Puedes ejecutar y visualizar este proyecto directamente en la nube haciendo clic en el siguiente botón:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1DwifCbjMfc9Q5JPwKoW1by5naEliJusm#scrollTo=3d7a4bf6)

---

## 🛠️ Objetivos del Proyecto

El flujo de trabajo se divide en las siguientes etapas críticas:

### 1. Extracción de Datos (Web Scraping)
- Navegación y extracción de datos estructurados de la página [Books to Scrape](http://books.toscrape.com/).
- Construcción de un `DataFrame` inicial con títulos y precios.

### 2. Preprocesamiento de Texto (NLP)
Limpieza profunda del corpus para normalizar los datos:
- Conversión a minúsculas.
- Eliminación de *stop-words* (palabras comunes sin valor semántico).
- Remoción de caracteres especiales y números.
- Generación de la base de datos `datos_limpios`.

### 3. Análisis de n-gramas y Visualización
- Creación de una tabla de frecuencias para n-gramas.
- Generación de una **Nube de Palabras (WordCloud)** para identificar visualmente las tendencias temáticas en los títulos de los libros.

### 4. Matriz Term Frequency (TF) y Análisis de Precios
- Construcción de una matriz de términos donde las filas representan los libros y las columnas el corpus de palabras.
- Binariización de variables (presencia/ausencia de palabras clave).
- Análisis comparativo del precio promedio de los libros basado en la aparición de términos específicos.

### 5. Visualización Estadística
- Implementación de gráficos de barras que relacionan palabras clave con el valor del libro.
- Interpretación de la asociación positiva o negativa entre el léxico del título y el costo comercial.

---

## 📋 Requisitos
El proyecto utiliza las siguientes librerías de Python:
- `pandas` (Manipulación de datos)
- `BeautifulSoup4` o `Scrapy` (Web Scraping)
- `nltk` o `spaCy` (NLP)
- `matplotlib` / `seaborn` (Visualización)
- `wordcloud` (Generación de nubes de palabras)

---

## ✒️ Autor
* **Tu Nombre** - [Tu Perfil de GitHub](https://github.com/tu-usuario)
