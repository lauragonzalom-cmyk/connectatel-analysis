# Análisis ConnectaTel

## 📌 Objetivo del proyecto

El objetivo de este proyecto es analizar los datos de los clientes de ConnectaTel para identificar patrones de uso, segmentar a los usuarios y detectar oportunidades de mejora en la oferta comercial de la compañía.

## 📊 Datasets utilizados

Se utilizaron tres datasets:

* `plans.csv`: información sobre los planes de ConnectaTel.
* `users_latam.csv`: información sobre los clientes, como edad, ciudad, plan y fecha de registro.
* `usage.csv`: información sobre el uso de llamadas y mensajes.

## 🔎 Etapas del análisis

El análisis se realizó en las siguientes etapas:

1. Carga y exploración de los datasets.
2. Identificación y tratamiento de valores ausentes y datos anómalos.
3. Conversión y corrección de variables de fecha y otros tipos de datos.
4. Creación de métricas de uso por cliente: llamadas, mensajes, minutos y consumo de datos.
5. Análisis de las distribuciones y detección de outliers.
6. Segmentación de los clientes según su nivel de uso y edad.
7. Visualización de los segmentos.
8. Elaboración de un análisis ejecutivo con conclusiones y recomendaciones para el negocio.

## 🛠️ Herramientas utilizadas

* Python
* Pandas
* NumPy
* Seaborn
* Matplotlib
* Google Colab
* GitHub

## ▶️ Cómo ejecutar el proyecto

El análisis se encuentra en el notebook Analisis_ConnectaTel.ipynb, disponible en este repositorio de GitHub.

Para reproducir el análisis:

*Descargar o abrir el archivo Analisis_ConnectaTel.ipynb desde el repositorio.
*Abrir el notebook utilizando Jupyter Notebook, JupyterLab o Google Colab.
*Disponer de los tres datasets utilizados en el proyecto.
*Ejecutar las celdas del notebook en orden.
*Revisar las visualizaciones, segmentaciones y conclusiones obtenidas.

## 📁 Estructura del proyecto

```text
connectatel-analysis/
│
├── Analisis_ConnectaTel.ipynb
├── README.md
└── datasets/
    ├── plans.csv
    ├── users_latam.csv
    └── usage.csv
```

## 📌 Resultados principales

El análisis permitió identificar diferentes perfiles de clientes según su edad y nivel de uso. También se detectaron valores extremos en llamadas, mensajes y minutos de uso.

Los outliers de consumo se conservaron porque pueden representar clientes reales con un nivel de utilización elevado y, por tanto, pueden ser relevantes para definir estrategias comerciales.

A partir de los segmentos identificados, se plantean oportunidades para adaptar los planes a diferentes niveles de consumo y potenciar la migración de clientes hacia planes de mayor valor.

## 👤 Autor

Proyecto realizado como parte del programa de formación de Data Analyst de TripleTen.
