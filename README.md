<div align="center">
  <img src="src/Head.png" alt="Conceptos básicos de Python">
</div>


# Proyecto ETL con Python: Construyendo un Pipeline Básico

Este proyecto trata de la creación de un pipeline básico de ETL (Extract, Transform, Load) utilizando herramientas como Google Colab o en este caso Visual Studio Code, bibliotecas de Python y SQL. Aprendi a extraer datos de diversas fuentes, aplicar transformaciones, cargar datos en una base de datos y automatizar todo el proceso. 

## Descripción del Proyecto

El objetivo de este proyecto es abordar el desafío de consolidar y centralizar datos dispersos en múltiples archivos de hojas de cálculo o CSV. A menudo, este escenario se conoce como el "caos de Excel". La solución propuesta implica migrar y organizar estos datos utilizando Python y las bibliotecas pandas y sqlite.

A lo largo del proyecto, aprenderás a:

- Extraer información de archivos CSV.
- Crear y manipular DataFrames en Python.
- Aplicar transformaciones a los datos.
- Cargar los datos en una base de datos SQLite.

Este proyecto te equipará con las habilidades necesarias para abordar desafíos en el campo de la extracción, transformación y carga de datos.

## Requisitos Previos

Antes de comenzar, asegúrate de tener una cuenta de Gmail para interactuar con Google Colab. También se recomienda tener conocimientos previos en programación en Python.

## Configuración Inicial

1. Accede a Google Colab y/o Visual Studio Code.
2. Crea un nuevo Notebook llamado "ETL" con la extensión ".ipynb".
3. Importa la biblioteca pandas utilizando la sentencia `import pandas as pd`.

## Obtención de Datos

Para iniciar el proyecto, sube el archivo CSV con el que trabajarás a Google Colab utilizando la opción "Subir archivo". Luego, lee el archivo CSV en un DataFrame de pandas.

```python
# Leer archivo CSV
import pandas as pd

archivo_csv = 'ruta/al/archivo.csv'
datos = pd.read_csv(archivo_csv)
```


<div align="center">
  <img src="src/Certificate_ILBERT Alarcon.png" alt="Conceptos básicos de Python">
</div>