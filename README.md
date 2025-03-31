# 📈 S&P 500 Proyect – Análisis Exploratorio de Acciones

Análisis exploratorio de datos históricos de acciones pertenecientes al índice S&P 500. Este proyecto se enfoca en empresas tecnológicas como Amazon (AMZN), Google (GOOGL) y Apple (AAPL), utilizando archivos CSV individuales por empresa.

---

## 📚 Tabla de Contenidos
- 🧠 ¿Qué incluye este proyecto?
- 🔍 Análisis realizado
  1. Carga de archivos desde Google Drive
  2. Visualización de rutas y selección de empresas
  3. Limpieza y exploración de datos
  4. Análisis individual de acciones (open, close, volume)
  5. Visualización de tendencias de precios
  6. Cálculo de estadísticas y métricas clave
- 💻 Tecnologías y librerías utilizadas
- 🚀 Resultado
- ⚙️ Cómo ejecutar este proyecto

---

## 🧠 ¿Qué incluye este proyecto?
✅ Integración con Google Drive para cargar datos automáticamente  
✅ Exploración interactiva de rutas y selección manual de archivos CSV  
✅ Análisis detallado de acciones específicas (AMZN, GOOGL, AAPL)  
✅ Visualización de tendencias y volumen de transacciones  
✅ Cálculo de estadísticas como medias móviles y máximos/mínimos  
✅ Preparación para análisis financiero o modelos de predicción  

---

## 🔍 Análisis realizado

### 1. Carga de Archivos desde Google Drive
- Se monta Google Drive y se accede a una carpeta con más de 500 archivos CSV de empresas del S&P 500.
- Se utiliza la librería `glob` para listar automáticamente todos los archivos disponibles.

### 2. Visualización de rutas y selección manual
- Se muestran todas las rutas de archivos para facilitar la selección de empresas específicas.
- El usuario puede elegir manualmente qué acciones analizar (por ejemplo, Amazon, Apple, Google).

### 3. Limpieza y exploración de datos
- Se eliminan valores nulos.
- Se verifican tipos de datos y rangos de fechas para cada acción.

### 4. Análisis individual de acciones
- Se grafican las variables `Open`, `Close`, `High`, `Low`, y `Volume`.
- Se analizan patrones y movimientos de precios diarios.

### 5. Visualización de tendencias
- Se grafican líneas de precios a lo largo del tiempo.
- Se aplican medias móviles para detectar tendencias.

### 6. Cálculo de estadísticas y métricas
- Promedios móviles, desviaciones estándar, y máximos/mínimos por periodo.
- Preparación para modelos futuros de predicción de precios.

---

## 💻 Tecnologías y librerías utilizadas
- Python 3
- Google Colab
- Google Drive
- Pandas
- Matplotlib
- Seaborn
- glob
- os

---

## 🚀 Resultado
Este proyecto proporciona un análisis claro y reproducible del comportamiento histórico de empresas clave en el mercado bursátil. Permite entender patrones de precios, analizar volúmenes de transacción, y preparar los datos para un análisis financiero o predicciones con modelos de Machine Learning.

---

## ⚙️ Cómo ejecutar este proyecto

1. Abre el notebook `Stock_price_analysis.ipynb` en Google Colab.
2. Asegúrate de montar Google Drive:
```python
from google.colab import drive
drive.mount('/content/drive')
