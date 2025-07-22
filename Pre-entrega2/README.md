
# 📊 Pre-Entrega 2 - Limpieza y Análisis Exploratorio de Producción de Gas Natural en Argentina

Este documento corresponde a la segunda etapa del proyecto grupal de Data Science del programa Ingenias+. En esta fase se trabajó con los datos reales sobre la producción de gas natural en Argentina, con el objetivo de comprender su estructura, calidad y potencial analítico, como base para el desarrollo posterior de modelos predictivos.

---

🎯 **Objetivo de esta etapa**

Preparar los datos, identificar patrones iniciales y realizar un análisis exploratorio profundo que permita entender la dinámica de la producción de gas natural, con especial atención a la evolución de los recursos no convencionales (shale y tight).
Esta etapa incluyó:

  * Carga y revisión de datasets
  * Limpieza de datos (tratamiento de nulos, formatos y estandarización)
  * Transformaciones necesarias para análisis conjuntos
  * Análisis exploratorio de variables clave
  * Visualización de tendencias por cuenca y tipo de recurso

---

👩‍💻 **Integrantes - Equipo 5**

- Fabiana Yamila Mansilla

- Daniela Perea

---

🗂️ **Datasets utilizados**

📘 Dataset1: Serie histórica de producción de Gas Natural (Capítulo IV)
  * Frecuencia: Mensual
  * Variables: Año, mes, volumen total, promedio diario, cuenca, tipo de recurso
  * Utilidad: Permite observar la evolución nacional y regional del gas, y diferenciar entre recursos convencionales y no convencionales

📘 Dataset2: Producción de Pozos de Gas y Petróleo No Convencional
  * Frecuencia: Mensual por pozo
  * Variables: Empresa, pozo, cuenca, ubicación, tipo de recurso, volumen extraído
  * Utilidad: Permite analizar la producción a nivel micro, por pozo, empresa y recurso (shale, tight)

---

⚙️ **Proceso de trabajo**

**0. Carga e inspección de los datasets**
   
  * Revisión de dimensiones, tipos de datos y primeros registros
  * Limpieza y transformación
  * Eliminación de valores nulos o irrelevantes
  * Conversión de fechas y normalización de categorías
  * Unificación de criterios entre ambos datasets para integraciones futuras

**1. Análisis exploratorio**
   
  * Evolución de la producción nacional y por cuenca (Dataset1)
  * Análisis de pozos no convencionales (Dataset2)
  * Identificación de tendencias de crecimiento en shale y tight
  * Agrupaciones anuales para reducir ruido mensual y mejorar visualización

---

📚 **Fuentes de datos**
  * Dataset1 - Producción histórica por cuenca y subtipo (Capítulo IV)
  * Dataset2 - Producción por pozo (no convencional)

---

🛠️ **Herramientas utilizadas**
  * Lenguaje: Python 3.10
  * Análisis y visualización: pandas, numpy, matplotlib, seaborn, plotly, scipy
  * Entorno: Google Colab, Jupyter Notebook, GitHub

---

🔍 **Conclusiones preliminares**

Se estableció una base de datos confiable y estructurada que permitirá el desarrollo de modelos más avanzados en etapas posteriores. Se confirmaron diferencias claras entre cuencas y tipos de recursos, destacando el crecimiento sostenido de la producción no convencional, especialmente en la cuenca Neuquina. El análisis exploratorio permitió validar hipótesis iniciales y detectar patrones clave, consolidando los fundamentos para los modelos predictivos de la próxima etapa.

---

**Fecha de entrega**: 14/05/2025
