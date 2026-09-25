Análisis de datos — SuperTienda
Descripción del proyecto

Proyecto de análisis de datos realizado durante mi formación en Data Analytics, utilizando información de ventas de una empresa ficticia llamada SuperTienda.

El objetivo fue transformar y analizar los datos para obtener información útil sobre las ventas, ganancias y comportamiento de los clientes, utilizando diferentes herramientas de análisis y visualización.

El proyecto se desarrolló en tres etapas: preparación y análisis de datos, visualización en Power BI y segmentación mediante clustering.

Herramientas utilizadas:
Python
Pandas
SQL
Power BI
Google Colab
CSV

Hito 1 — Preparación y análisis de datos

En la primera etapa se trabajó con una base de datos de SuperTienda.

Se realizó:

Extracción de información mediante consultas SQL.
Selección de las tablas necesarias para el análisis.
Integración de información de clientes, pedidos, productos y ubicación.
Limpieza y preparación de los datos utilizando Python y Pandas.
Creación de variables necesarias para el análisis.
Generación de un dataset final en formato CSV.
Variables principales

Entre las variables utilizadas se encuentran:
Ventas
Cantidad
Descuento
Ganancia
Margen de Ganancia
Categoría
Región
Segmento

El Margen de Ganancia se incorporó como variable calculada para complementar el análisis de rentabilidad.

Hito 2 — Análisis y visualización con Power BI

En la segunda etapa se desarrolló un dashboard utilizando Power BI para facilitar la interpretación de los resultados.

El dashboard incluye indicadores y visualizaciones sobre:

Ganancias por categoría.
Evolución de ventas y ganancias.
Ganancias por región.
Ganancias por segmento.
Indicadores generales de ventas y ganancias.

Principales resultados:

A partir del análisis se observaron diferentes comportamientos:

Tecnología fue la categoría con mayor ganancia.
La región Centro presentó las mayores ganancias, seguida por la región Sur.
El segmento Corporativo presentó las mayores ganancias.
Se observó una disminución en la evolución de ventas y ganancias a partir de 2024.

Hito 3 — Segmentación mediante Clustering

En la tercera etapa se aplicó un modelo de K-Means para identificar grupos con características similares.

Las variables utilizadas fueron:
Ventas
Ganancia
Margen de Ganancia

Antes de aplicar el algoritmo se realizó una estandarización de las variables mediante StandardScaler.

Para determinar la cantidad de grupos se utilizó el método del codo, seleccionando posteriormente 3 clusters.

📊 Características de los clusters
ClusterVentas promedioGanancia promedioMargen promedio
0	1.465,01	185,10	12,65%
1	4.002,75	1.493,51	37,75%
2	1.021,04	377,69	37,70%

Los grupos permiten observar diferencias entre los registros según su nivel de ventas, ganancia y margen.

💡 Conclusiones

El análisis permitió identificar diferencias relevantes en el comportamiento de las ventas y la rentabilidad según categoría, región y segmento.

La aplicación de técnicas de clustering permitió además encontrar grupos de características similares a partir de variables relacionadas con ventas y rentabilidad.

Este proyecto permitió aplicar de manera práctica conceptos de:

SQL → Python/Pandas → análisis de datos → Power BI → Machine Learning no supervisado.

Objetivo:
Este proyecto forma parte de mi formación en Data Analytics y representa una aplicación práctica de herramientas de análisis, visualización y segmentación de datos.

Tecnologías: Python · Pandas · SQL · Power BI · K-Means
