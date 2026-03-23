# Análisis de Salud Mundial con Python y Pandas

## Autor
**Maeñyin**

## Descripción del proyecto
Este proyecto presenta un análisis exploratorio de un dataset de salud mundial utilizando Python y Pandas.  
El objetivo es examinar indicadores de salud en distintos países, identificar patrones relevantes y aplicar procesos básicos de limpieza, transformación, filtrado y agrupación de datos.

## Descripción del dataset
El dataset utilizado es **`salud_mundial.csv`**. Contiene información de **159 países** y **13 columnas** relacionadas con indicadores de salud y desarrollo.

### Variables incluidas:
- `pais`
- `region`
- `nivel_ingresos`
- `esperanza_vida`
- `gasto_salud_usd`
- `mortalidad_infantil`
- `medicos_por_1000`
- `poblacion_urbana_pct`
- `obesidad_pct`
- `diabetes_pct`
- `tabaquismo_pct`
- `camas_hospital_por_1000`
- `vacunacion_pct`

### Fuente
Dataset suministrado como parte de la actividad académica.

## Cómo ejecutar el notebook
Sigue estos pasos para ejecutar el proyecto correctamente:

1. Descarga o ubica el archivo **`salud_mundial.csv`** en la misma carpeta del notebook.
2. Abre **Jupyter Notebook** o **Google Colab**.
3. Carga el archivo del notebook del proyecto.
4. Asegúrate de tener instalada la librería **Pandas**.
5. Ejecuta la importación:
   ```python
   import pandas as pd


   Hallazgos principales

A partir del análisis realizado, se obtuvieron los siguientes hallazgos:

La esperanza de vida promedio mundial en el dataset es de aproximadamente 71.09 años.
Europa es la región con la mayor esperanza de vida promedio (77.65 años), mientras que África presenta la menor (63.51 años).
Se identificó que 39 países tienen una vacunación superior al 90%.
La región con la mayor tasa promedio de obesidad es Europa, con aproximadamente 23.65%.
Los países con nivel de ingresos bajo presentan una mortalidad infantil promedio considerablemente más alta que otras categorías.
Tecnologías usadas

En este proyecto se utilizaron las siguientes herramientas:

Python
Pandas
Jupyter Notebook
Git
GitHub
Estructura del proyecto
proyecto/
│── salud_mundial.csv
│── analisis_salud_mundial.ipynb
│── README.md
Conclusión

Este proyecto permitió aplicar conceptos fundamentales de análisis de datos con Python, incluyendo manipulación de estructuras, limpieza de valores nulos, análisis estadístico, filtrado de información y agrupación de variables. Además, facilitó la interpretación de indicadores de salud a nivel mundial mediante el uso de herramientas tecnológicas ampliamente utilizadas en ciencia de datos.


