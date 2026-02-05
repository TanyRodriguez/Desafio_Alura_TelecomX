# 📊 Telecom X Latam – Limpieza y Tratamiento de Datos

Este repositorio contiene un notebook en Python enfocado en la **limpieza, exploración y preparación de datos** para el análisis de churn (evasión de clientes) en una empresa de telecomunicaciones de Latinoamérica.

El objetivo principal es dejar el dataset listo para análisis exploratorio, modelado o visualización, asegurando calidad, consistencia y tipos de datos correctos.

---

## 📁 Contenido del repositorio

- `Challenge_TelecomX_Latam.ipynb`  
  Notebook principal con el proceso completo de:
  - Exploración de datos
  - Limpieza
  - Transformación de variables

---

## 🎯 Objetivo del proyecto

- Analizar la estructura del dataset de clientes de telecomunicaciones  
- Corregir problemas comunes de calidad de datos  
- Preparar la información para análisis de **churn** (evasión de clientes)  

---

## 🧠 Dataset (descripción general)

El dataset contiene información de clientes, incluyendo:

- **customerID** – Identificador único del cliente  
- **gender** – Género  
- **SeniorCitizen** – Indica si el cliente es adulto mayor  
- **Partner / Dependents** – Información familiar  
- **tenure** – Antigüedad del cliente  
- **PhoneService / InternetService** – Servicios contratados  
- **Contract** – Tipo de contrato  
- **MonthlyCharges** – Cargos mensuales  
- **TotalCharges** – Cargos totales  
- **Churn** – Indica si el cliente abandonó el servicio (`Yes / No`)  

---

## 🔍 Proceso realizado en el notebook

### 1. Exploración inicial
- Revisión de columnas y tipos de datos
- Identificación de valores nulos y registros inconsistentes

### 2. Limpieza de datos
- Conversión de variables numéricas mal tipadas
- Tratamiento de valores faltantes
- Normalización de formatos

### 3. Preparación para análisis
- Dataset final listo para:
  - Análisis exploratorio (EDA)
  - Modelos de predicción de churn
  - Visualización y dashboards

---

## 🛠️ Tecnologías utilizadas

- **Python 3**
- **Pandas**
- **NumPy**
- **Jupyter Notebook / Google Colab**

---

## ▶️ Cómo ejecutar el proyecto

### Opción 1: Google Colab
Abrir el notebook directamente en Google Colab.

### Opción 2: Local
1. Clona el repositorio:
   ```bash
   git clone https://github.com/tu-usuario/telecom-x-latam.git
   ```
2. Instala las dependencias:
   ```bash
   pip install pandas numpy
   ```
3. Abre el notebook:
   ```bash
   jupyter notebook Challenge_TelecomX_Latam.ipynb
   ```

---

## 📈 Próximos pasos sugeridos

- Análisis exploratorio avanzado (EDA)
- Visualización de churn por segmento
- Modelos de machine learning para predicción de churn
- Feature engineering

---

## 👩‍💻 Autor

Proyecto desarrollado como parte de un **challenge de análisis de datos**, enfocado en buenas prácticas de limpieza y preparación de información para negocio.

---

## 📄 Licencia

Este proyecto se comparte con fines educativos y de demostración.
