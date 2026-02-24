#📊 Challenge 1 - Data Science LATAM

Análisis exploratorio de datos (EDA) y evaluación de rendimiento de 4 tiendas utilizando Python y herramientas de visualización.

Este proyecto forma parte del Challenge 1 - Data Science LATAM, donde se analizan métricas clave de negocio para generar una recomendación estratégica basada en datos.

#🎯 Objetivo del Proyecto

Evaluar el rendimiento de cuatro tiendas a partir de sus datos de ventas para:

Analizar facturación total y por tienda

Evaluar ventas por categoría

Calcular calificación promedio de clientes

Identificar productos más y menos vendidos

Analizar costo promedio de envío

Evaluar ingresos mensuales y acumulados

Generar una recomendación basada en métricas de desempeño

🛠 Tecnologías Utilizadas

Python 3

pandas

matplotlib

seaborn

Google Colab

📂 Fuente de Datos

Los datos fueron cargados directamente desde archivos CSV públicos alojados en GitHub:

tienda_1.csv

tienda_2.csv

tienda_3.csv

tienda_4.csv

Cada dataset contiene información como:

Precio

Categoría del Producto

Calificación

Costo de envío

Fecha de compra

📈 Análisis Realizados
1️⃣ Facturación Total

Se calculó la suma total de ventas por tienda y el total general, permitiendo identificar qué tienda genera mayores ingresos.

2️⃣ Ventas por Categoría

Agrupación por categoría de producto para identificar:

Categorías con mayor contribución a ingresos

Dependencia comercial por tipo de producto

3️⃣ Calificación Promedio

Se analizó la media de calificación por tienda para evaluar percepción del cliente.

4️⃣ Productos Más y Menos Vendidos

Se consolidaron los datasets para identificar:

Productos más populares

Productos con menor rotación

5️⃣ Costo Promedio de Envío

Se calculó el promedio de costo de envío por tienda para analizar impacto en rentabilidad.

6️⃣ Análisis Temporal

Se realizó:

Conversión de fechas a formato datetime

Agrupación mensual

Cálculo de ingresos mensuales

Cálculo de ingreso acumulado

Cálculo de lucro hipotético (Precio - Costo de envío)

Esto permitió visualizar tendencias y comportamiento de crecimiento.

📊 Visualizaciones Generadas

Gráfico de barras de ingresos totales por tienda

Ingreso promedio por venta

Boxplot de costo de envío vs calificación

Ingresos mensuales por tienda

Ingreso acumulado en el tiempo

Las visualizaciones permiten identificar patrones de rendimiento y diferencias competitivas entre tiendas.

🧠 Conclusión del Análisis

A partir del análisis de ingresos, rendimiento y calidad, se realizó una recomendación estratégica identificando la tienda con menor desempeño relativo.

La decisión se basó en:

Menor facturación

Menor crecimiento acumulado

Relación entre calificación y costos

Rentabilidad hipotética

🚀 Cómo Ejecutar el Proyecto
Opción 1: Google Colab

Abrir el archivo .ipynb en Google Colab

Ejecutar las celdas en orden

Opción 2: Local
git clone <URL-del-repositorio>
cd challenge1-data-science-latam
pip install pandas matplotlib seaborn
jupyter notebook
📁 Estructura del Proyecto
📦 Challenge1_Data_Science_Latam
 ┣ 📜 Challenge1_Data_Science_Latam.ipynb
 ┗ 📄 README.md
💡 Habilidades Demostradas

Limpieza y transformación de datos

Agrupación y agregación con pandas

Manipulación de fechas

Análisis exploratorio (EDA)

Visualización profesional de datos

Generación de conclusiones basadas en métricas

📌 Posibles Mejoras

Implementar análisis de correlación más profundo

Incorporar métricas de margen real

Aplicar modelos predictivos

Automatizar dashboard con Streamlit o Power BI
