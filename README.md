# 📊 Análisis de Precios de Acciones del S&P 500

Este proyecto tiene como objetivo analizar los datos históricos de precios de acciones de empresas incluidas en el índice S&P 500. Se ha desarrollado en Python utilizando Google Colab, con los datos almacenados en Google Drive. El enfoque se centra en empresas tecnológicas clave como **Amazon (AMZN)**, **Google (GOOGL)** y **Apple (AAPL)**.

## 🗂️ Estructura del Proyecto

- `Stock_price_analysis.ipynb`: Notebook principal con el análisis de los datos.
- Carpeta en Drive con archivos `.csv` individuales para cada acción del S&P 500.

## 🚀 Funcionalidades

- Carga automática de múltiples archivos `.csv` desde una carpeta en Google Drive.
- Exploración y visualización de rutas para selección manual de acciones.
- Limpieza, análisis y visualización de datos históricos de precios.
- Preparación de datos para futuras predicciones o modelos de aprendizaje automático.

## 🛠️ Tecnologías utilizadas

- Python 3
- Pandas
- Matplotlib / Seaborn
- Google Colab
- Google Drive API

## 🧠 Posibles extensiones

- Predicción de precios usando modelos de Machine Learning.
- Comparación del rendimiento entre diferentes empresas del S&P 500.
- Simulación de carteras de inversión.

## 📁 Cómo usar

1. Abre el notebook `Stock_price_analysis.ipynb` en Google Colab.
2. Asegúrate de montar tu Google Drive para acceder a los datos.
3. Ejecuta las celdas para cargar los archivos, seleccionar las empresas y analizar los precios.

```python
from google.colab import drive
drive.mount('/content/drive')
