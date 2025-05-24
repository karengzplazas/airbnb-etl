# 🏡 Proyecto ETL: Análisis de Datos de Airbnb con Pandas y MongoDB Atlas

## 📌 Resumen Ejecutivo

Este proyecto tiene como objetivo aplicar un flujo ETL (Extracción, Transformación y Carga) utilizando Python, Pandas y MongoDB Atlas. La fuente de datos es la colección pública `listingsAndReviews`, que contiene información detallada sobre alojamientos de Airbnb.

### 🎯 Objetivos:
- Extraer datos de MongoDB Atlas.
- Transformar los datos para limpieza y análisis.
- Analizar precios y tipos de propiedad.
- Exportar datos procesados a un archivo CSV.

---

## 1️⃣ Extracción de Datos

- Conexión a **MongoDB Atlas** mediante **MongoDB Compass**.
- Exportación de la colección `listingsAndReviews` a formato `.csv`.

> 💬 **Pregunta exploratoria:** ¿Cuántos registros contiene la colección?

---

## 2️⃣ Transformación de Datos

- Conversión del CSV a `DataFrame` con `pandas`.
- Limpieza:
  - Eliminación de registros con valores nulos en `price` o `review_scores.review_scores_rating`.
  - Conversión de `price` a tipo numérico (remoción de símbolos).

---

## 3️⃣ Análisis de Datos

- Precio promedio por tipo de propiedad (`property_type`).
- Top 5 de tipos de propiedad con más alojamientos.

> 💬 **Pregunta exploratoria:** ¿Cuál es el tipo de propiedad más común?

---

## 4️⃣ Exportación de Datos

- Guardado del DataFrame limpio y transformado en:  
  📄 `airbnb_cleaned.csv`

---

## ⚙️ Tecnologías Utilizadas

- Python 3.x  
- Pandas  
- MongoDB Atlas  
- MongoDB Compass  
- Google Colab o Jupyter Notebooks

---

## 📁 Estructura del Repositorio

