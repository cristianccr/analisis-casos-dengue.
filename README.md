# Análisis de Casos de Dengue en Argentina

[Abrir cuaderno en Colab](https://colab.research.google.com/github/cristianccr/analisis-casos-dengue/blob/main/Modulo2.ipynb)

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



# Análisis de Casos de Dengue en Argentina

## Descripción

Este proyecto analiza los casos confirmados de Dengue en Argentina para el año 2024. Utiliza herramientas como Python, SQLite y Plotly para analizar los datos y generar visualizaciones interactivas.

El objetivo del proyecto es cargar los datos desde un archivo CSV, almacenarlos en una base de datos SQLite, y crear visualizaciones interactivas para explorar los casos confirmados por semana epidemiológica, grupo etario y departamento de residencia.

## Dataset

**Dataset utilizado:** Casos confirmados de Dengue en Argentina (2024).  
**Fuente:** [Enlace al dataset](https://github.com/cristianccr/analisis-casos-dengue/blob/main/casos_dengue.csv)

El dataset contiene información sobre los casos confirmados de Dengue en Argentina, incluyendo variables como la semana epidemiológica, el grupo etario y el departamento de residencia.

## Cómo abrir el cuaderno en Google Colab

Para abrir el cuaderno en Google Colab y ejecutar el análisis, sigue estos pasos:

1. Dirígete a [https://colab.research.google.com/](https://colab.research.google.com/).
2. En la página de inicio de Colab, selecciona **"Abrir cuaderno"**.
3. Elige la opción **"Desde GitHub"**.
4. En el campo de búsqueda, ingresa la URL del repositorio:  
   `https://github.com/cristianccr/analisis-casos-dengue`
5. Selecciona el archivo `Modulo2.ipynb` para abrir el cuaderno de Jupyter en Colab.

## Cómo usar el dataset en Google Colab

Para realizar el análisis, primero necesitas descargar el archivo `casos_dengue.csv` y cargarlo en Google Colab. Sigue estos pasos:

### 1. Descargar el dataset:
- Haz clic en el siguiente enlace para acceder al archivo CSV:  
[casos_dengue.csv](https://github.com/cristianccr/analisis-casos-dengue/blob/main/casos_dengue.csv).
- Luego, haz clic en **"Download"** para guardar el archivo en tu computadora.

### 2. Subir el archivo a Google Colab:
- Una vez abierto el cuaderno en Colab, usa este código para cargar el archivo en tu entorno:

```python
from google.colab import files
uploaded = files.upload()






