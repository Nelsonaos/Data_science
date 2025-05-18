# Análisis Predictivo en Clientes de un Servicio de Streaming

## 📌 **Introducción**

Este proyecto tiene como objetivo principal explorar un conjunto de datos de 3,500 clientes de un servicio de streaming, para determinar si es posible predecir la baja de clientes (*churn*). Además, se busca identificar qué variables tienen mayor relevancia en esta problemática y cuáles no aportan valor significativo.

---

## 🎯 **Planteamiento del Problema y Hipótesis**

### **¿Cuáles son las variables que influyen en la cancelación de clientes?**

**Hipótesis:**

* Los clientes con menor tiempo de suscripción son más propensos a cancelar.
* Una baja satisfacción del cliente está correlacionada con una mayor tasa de churn.
* Factores como el tipo de dispositivo utilizado, la región y el historial de pagos pueden influir en la cancelación.

---

## 🔍 **Exploración de los Datos (EDA)**

Para abordar este problema, se realizó un análisis exploratorio que incluyó la identificación de tipos de variables y la visualización de datos clave.

### 🔹 **Tipos de Variables en el DataFrame**

* **Variables categóricas:** `Device Used Most Often`, `Genre Preference`, `Region`, `Payment History`, `Subscription Plan`, `Churn Status`, `Promotional Offers Used`

* **Variables numéricas:** `Subscription Length (Months)`, `Customer Satisfaction Score (1-10)`, `Daily Watch Time (Hours)`, `Engagement Rate (1-10)`, `Monthly Income ($)`, `Number of Profiles Created`

---

## 📊 **Análisis Exploratorio (EDA) con Gráficos**

1. **Distribución de la Variable Objetivo**

   * Se observó un desbalance en `Churn Status`, con una mayor proporción de clientes activos.

2. **Distribución de Variables Numéricas**

   * Se analizaron las variables de satisfacción, ingresos mensuales, edad, tiempo de uso y tiempo de suscripción. Algunas presentan sesgos, mientras que otras son más uniformes.

3. **Tiempo de Suscripción y Churn**

   * Los clientes con más meses de permanencia tienden a continuar en el servicio, indicando un fuerte factor de retención.

4. **Satisfacción del Cliente**

   * Existe una tendencia donde clientes con menor satisfacción tienden a cancelar el servicio.

5. **Dispositivo Utilizado**

   * Un heatmap mostró que usuarios en *smartphones* y *laptops* tienen mayores tasas de churn, mientras que aquellos en *Smart TVs* y *tablets* presentan menores bajas.

6. **Distribución de la Satisfacción**

   * Los niveles de satisfacción entre 6 y 9 son los más comunes. Los niveles inferiores a 5 están vinculados con mayores bajas.

7. **Tipo de Plan y Churn**

   * El plan básico muestra una mayor proporción de cancelaciones, posiblemente por una percepción menor de valor.

---

## 📌 **Conclusión Preliminar**

El análisis exploratorio sugiere que ciertas variables son clave para predecir el churn:

* Tiempo de suscripción
* Satisfacción del cliente
* Tipo de dispositivo
* Plan de suscripción
* Historial de pagos

Estas variables serán la base para la construcción de un modelo de *Machine Learning* (XGBoost) orientado a predecir la probabilidad de churn y anticipar acciones para prevenirlo.

##   **Proyecto**

1. https://colab.research.google.com/drive/1wNqC2QcociPPvRyJ2FW5mFhTZksCE_b3#scrollTo=ekbyvgFTmmAn

## 🚀 **Ejecucion**

1. Implementación de un modelo predictivo (*XGBoost*).
2. Evaluación del modelo utilizando métricas de clasificación (Accuracy, F1-Score, Recall).
3. Identificación de clientes en riesgo para optimización de campañas de marketing y fidelización.

---

## 🛠️ **Tecnologías Utilizadas**

* Python (Pandas, Seaborn, Matplotlib, Scikit-Learn, XGBoost)
* Jupyter Notebook
* Git para el control de versiones

---



## 📞 **Contacto**
