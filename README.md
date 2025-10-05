
------------------------------------------------------------
# Análisis de Casos de Dengue en Argentina

## Descripción

Este proyecto analiza los casos confirmados de Dengue en Argentina durante el año 2024. Utiliza herramientas como Python, SQLite y Plotly para cargar los datos desde un archivo CSV, almacenarlos en una base de datos SQLite y generar visualizaciones interactivas de los casos confirmados por semana epidemiológica, grupo etario y departamento de residencia.

## Dataset

**Dataset utilizado:** Casos confirmados de Dengue en Argentina (2024).  
**Fuente:** [Enlace al dataset](https://github.com/cristianccr/analisis-casos-dengue/blob/main/casos_dengue.csv)

## Cómo ejecutar el proyecto

### Paso 1: Clonar el repositorio

Para comenzar, clona el repositorio en tu máquina local usando el siguiente comando:

git clone https://github.com/cristianccr/analisis-casos-dengue.git

### Paso 2: Subir el archivo a Google Colab

1. Abre el cuaderno en **Google Colab** desde este [enlace](https://colab.research.google.com/).
2. Haz clic en **"Abrir cuaderno"** y selecciona **"Desde GitHub"**.
3. Introduce la URL de este repositorio:  
   `https://github.com/cristianccr/analisis-casos-dengue`
4. Selecciona el archivo `Modulo2.ipynb`.

### Paso 3: Cargar el dataset

1. **Descarga el dataset** `casos_dengue.csv` desde el repositorio.
2. En Google Colab, usa el siguiente código para cargar el archivo:

   - Ve a la sección de carga de archivos y selecciona el archivo CSV desde tu computadora.

### Paso 4: Ejecutar el análisis

Una vez que hayas cargado el archivo, ejecuta las celdas en el cuaderno de Google Colab. Esto generará los gráficos interactivos sobre los casos confirmados de Dengue.

## Requisitos

Antes de ejecutar el proyecto, asegúrate de tener las siguientes bibliotecas instaladas:

- `pandas`: Para manejar los datos.
- `plotly`: Para las visualizaciones interactivas.
- `sqlite3`: Para trabajar con la base de datos.

Si tienes el archivo `requirements.txt`, puedes instalar las dependencias ejecutando:

pip install -r requirements.txt







