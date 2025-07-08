# 📊 Pre-Entrega 4 - Modelos de Aprendizaje No Supervisados de Producción de Gas Natural en Argentina

Este documento forma parte del proyecto grupal de Data Science del programa Ingenias+, y corresponde a la cuarta etapa de entrega. En esta fase se trabajó con técnicas de **aprendizaje no supervisado** para generar modelos de aprendizaje de la producción de gas natural en Argentina, con base en los análisis realizados en las etapas anteriores.

---

### 🎯 Objetivo de esta etapa

El objetivo principal de este proyecto es aplicar algoritmos de clustering para identificar patrones y estructuras subyacentes en datos de producción de gas natural en Argentina. Esto permitirá descubrir características distintivas o comportamientos anómalos en las series históricas y en la producción de pozos no convencionales. Esta etapa incluye:

- Preprocesamiento y Transformación de datos de ambos dataset
- Implementación de modelos de **Clustering**
- Reducción de Dimesionalidad (PCA)
- Ajuste y optimización de **clusters**
- Comparación, Evaluación y Visualización de modelos

---

### 👩‍💻 Integrantes - Equipo 5

- Fabiana Yamila Mansilla  
- Daniela Perea

---

### 🧠 Modelos Supervisados Utilizados

Durante esta entrega se aplicaron distintos algoritmos de aprendizaje no supervisado con el objetivo de encontrar patrones en la producción de gas natural (tanto a nivel nacional como por pozo). Se trabajó principalmente con el **Dataset1 (serie histórica)** y el **Dataset2 (pozos no convencionales)**.

#### Modelos de Clustering:

- **K-Means**  
- **DBSCAN**
- **Gaussian Mixture Models (GMM)** (solo para Dataset2)

---

### ⚙️ Proceso de trabajo

##### 0. Carga e Inspección 
- Cargar los dataset.
- Analisis del Dataset.
- Procesamiento y Transformación.

##### 1. Selección y Creación de Variables
- Creación de Variables Temporales (solo Dataset1)
 Selección de características para clustering

##### 2. Preprocesamiento de Datos
- Manejo de Valores Nulos
- Escalado de Variables Numéricas
- Codificación de Variables Categóricas
- Detección y Manejo de Outliers

##### 3. Aplicación de Algoritmos de Clustering 
- **PCA:** Reducimos la dimensionalidad con PCA.
- **K-Means:** Determinación del número óptimo de clusters mediante el método del codo y el coeficiente de silueta. Visualización de los clusters utilizando PCA para reducción de dimensionalidad a 2D. 
- **DBSCAN:** Aplicación del algoritmo DBSCAN para identificar grupos de densidad.
- **GMM:** Aplicación del modelo de mezclas gaussianas para el clustering, con visualización de los clusters en 2D (usando PCA) y su distribución geoespacial. (solo Dataset2)

  ##### 4.  Análisis Exploratorio y Visualización de Clusters
  
- **Evaluación y Visualización:** Se evalúa la calidad de los clusters utilizando el silhouette_score y se visualizan los resultados.
- **Comparación de Modelos:** comparación del rendimiento y los resultados obtenidos por K-Means, DBSCAN y GMM, permitiendo una visión integral de sus fortalezas y debilidades en el contexto de los datasets de producción de gas natural.

---

### 🗂️ Estructura de la carpeta

📁 Pre-entrega4/  
│  
├── 📄 README.md ← Este archivo  
├── 📓 Pre-Entrega4_Equipo5.ipynb  
├── 📁 Dataset/ ← Subcarpeta con datasets originales 
│   ├── serie-histrica-de-produccin-de-gas-natural-por-cuenca-y-sub-tipo-de-recurso-captulo-iv-.csv
│   └── produccin-de-pozos-de-gas-y-petrleo-no-convencional.csv 


---

### 📚 Fuentes de datos

- Dataset1: [Serie histórica por cuenca y subtipo](http://datos.energia.gob.ar/dataset/serie-historica-de-produccion-de-gas-natural-por-cuenca-y-sub-tipo-de-recurso-captulo-iv)
- Dataset2: [Producción de pozos no convencionales](http://datos.energia.gob.ar/dataset/produccion-de-petroleo-y-gas-por-pozo)

---

### 🛠️ Herramientas utilizadas

- **Lenguaje:** Python 3.10
- **Análisis y visualización:** pandas, numpy, matplotlib, seaborn, plotly, scipy
- **Modelado predictivo:** sklearn (K-Means, DBSCAN, Gaussian Mixture Models)
- **Entorno:** Google Colab, Jupyter Notebook, GitHub

---

### 🔍 Conclusiones preliminares

- aaa


---
**Fecha de Entrega:** 10/07/2025

