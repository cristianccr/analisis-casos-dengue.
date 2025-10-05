# Análisis de Casos de Dengue en Argentina



## Descripción

Este proyecto analiza los casos confirmados de Dengue en Argentina para el año 2024, utilizando Python, SQLite y herramientas de visualización como Plotly.

El objetivo es cargar los datos desde un archivo CSV, almacenarlos en una base de datos SQLite, y crear visualizaciones interactivas para explorar los casos confirmados por semana epidemiológica, grupo etario y departamento de residencia.

## Dataset

**Dataset utilizado:** Casos confirmados de Dengue en Argentina (2024).  
**Fuente:** [Enlace al dataset](https://github.com/cristianccr/analisis-casos-dengue/blob/main/casos_dengue.csv)

### Cómo usar el dataset en Google Colab

Para que el análisis funcione correctamente, primero necesitas descargar el archivo `casos_dengue.csv` desde este repositorio y cargarlo en Google Colab.

1. **Descargar el dataset**:
   - Haz clic en el siguiente enlace para acceder al archivo CSV:  
   [casos_dengue.csv](https://github.com/cristianccr/analisis-casos-dengue/blob/main/casos_dengue.csv).
   - Una vez dentro, haz clic en **"Download"** para descargar el archivo en tu computadora.

2. **Subir el archivo a Google Colab**:
   - Después de abrir el cuaderno de Colab, usa el siguiente código para cargar el archivo en tu entorno de Colab:

     ```python
     from google.colab import files
     uploaded = files.upload()
     ```

   - Esto abrirá un cuadro de diálogo donde podrás seleccionar el archivo `casos_dengue.csv` desde tu computadora. Después de cargarlo, podrás continuar con el análisis ejecutando las celdas en el cuaderno de Colab.

## Motor de Base de Datos

**Motor de base de datos utilizado:** SQLite.  
El código para cargar los datos en la base de datos SQLite está listo, y puedes usar el script para crear la base de datos de manera sencilla.

## Pasos para configurar

1. Instala SQLite si no lo tienes instalado.
2. Corre el script `cargar_base_de_datos.py` para crear y cargar la base de datos.

## Dashboard

El dashboard interactivo utiliza Plotly para crear gráficos interactivos.

## Pasos para ejecutar el código en Google Colab

1. Abre el notebook en Colab usando el botón de arriba.
2. **Carga el archivo `casos_dengue.csv`** en Google Colab.
3. Ejecuta las celdas para cargar los datos, limpiar los valores y generar las visualizaciones interactivas.
4. El código para cargar los datos en la base de datos SQLite está listo, y puedes usar el script para crear la base de datos de manera sencilla.

## Carga del archivo en SQLite

El código para cargar los datos en la base de datos SQLite está listo, y puedes usar el script para crear la base de datos de manera sencilla.





