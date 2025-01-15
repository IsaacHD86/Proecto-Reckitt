# Proyecto-Reckitt
Ciencia de Datos.

La Empresa Reckitt México, es una empresa líder en el mercado en productos de higiene del hogar, salud y nutrición, con marcas como Vanish, Lysol, Tempra, Sico, Durex y Chocomilk, entre
muchas otras.

![image](https://github.com/user-attachments/assets/ac30f613-d90f-4165-8438-50861981b1a4)


## Descripción del Proyecto
Este proyecto se centra en analizar el rendimiento de ventas de la categoría Cloros y Blanqueadores de Ropa, una de las más importantes para Reckitt con la marca Vanish. Nuestro objetivo es identificar dónde estamos perdiendo presencia en los segmentos clave (Blanqueadores en Polvo, Líquido, Barra, etc.), determinar a nuestros principales competidores y proponer acciones estratégicas para mejorar. Además, evaluamos la estrategia para Lysol Sanitizer en el segmento de Sanitizantes de Ropa para determinar su efectividad en ganar participación de mercado.

El proyecto incluye análisis de datos, visualización, segmentación, construcción de modelos predictivos y la creación de un dashboard interactivo en Power BI para facilitar la toma de decisiones estratégicas.

## Objetivos
### Análisis de Datos:

Cargar, limpiar y transformar los datos utilizando Python y Pandas.
Consolidar los datos en un formato adecuado para el análisis.

### Visualización de Datos:

Crear visualizaciones con Python para entender la distribución de los datos y las relaciones entre variables.
Identificar tendencias, patrones y posibles áreas de mejora.

### Segmentación de Mercado:

Aplicar técnicas de clustering (como K-Means) para identificar segmentos clave donde Vanish tiene presencia y oportunidades de mejora.

### Base de Datos SQL:

Crear y gestionar una base de datos en SQL Server Management Studio (SSMS).
Cargar tablas relevantes y realizar consultas avanzadas para explorar los datos.

### Dashboard en Power BI:

Construir un dashboard interactivo que permita explorar los insights obtenidos, incluyendo análisis de ventas, productos y escenarios predictivos.

### Modelo Predictivo:

Desarrollar un modelo para prever las ventas futuras de productos clave como Vanish y Lysol, utilizando regresión lineal y metricas como MSE, MAE, R2-Score para evaluar el modelo.

# Metodología

### Fase 1: Preparación de Datos
* Carga de datos:

Tablas utilizadas: DIM_CATEGORY, DIM_PRODUCT, DIM_SEGMENT, DIM_CALENDAR, FACT_SALES.
Uso de Pandas para cargar datos desde archivos CSV o Excel.

* Limpieza de datos:

Eliminación de valores nulos, duplicados e inconsistencias.
Transformaciones para estandarizar los datos.

* Consolidación:

Unificación de los DataFrames relevantes en un conjunto de datos consolidado.
Guardado del conjunto para su análisis posterior.

### Fase 2: Exploración y Visualización de Datos.
* Análisis exploratorio:

Visualización de la distribución de ventas.
Análisis de tendencias de ventas a lo largo del tiempo.
Identificación de patrones y outliers.

* Herramientas utilizadas: Python (Matplotlib, Seaborn).

### Fase 3: Segmentación
Uso de clustering (K-Means) para identificar:
Segmentos clave en los que Vanish tiene presencia.
Áreas para mejorar la estrategia.

### Fase 4: Gestión en SQL.
* Creación de base de datos:
Estructura de las tablas en SSMS.

* Carga de datos:
Inserción de datos en las tablas creadas.

* Consultas:
Consultas básicas y avanzadas para explorar relaciones entre variables y generar insights.

### Fase 5: Desarrollo de Dashboard en Power BI

* Diseño de un dashboard interactivo que incluye:
Ventas por segmentos y productos.
Participación de mercado.
Escenarios predictivos y análisis de tendencias.

### Fase 6: Modelado Predictivo.

* Desarrollo del modelo:
Predicción de ventas futuras para Vanish y Lysol.
Métodos utilizados: Regresión y/o análisis de series de tiempo.

## Herramientas Utilizadas
Python: Pandas, Matplotlib, Seaborn, Scikit-learn.
SQL: SQL Server Management Studio (SSMS).
Power BI: Creación de dashboards interactivos.
GitHub: Control de versiones y documentación del proyecto.

## Resultados Esperados.
- Insights clave sobre los segmentos de mercado y la posición de la marca Vanish.
- Identificación de oportunidades para mejorar la estrategia de mercado.
- Predicciones de ventas confiables para productos clave.
- Un dashboard interactivo que permita a los stakeholders explorar los resultados de manera eficiente.

