Análisis de Casos de Dengue en Argentina

Abrir en Colab

Descripción

Este proyecto analiza los casos confirmados de Dengue en Argentina para el año 2024, utilizando Python, SQLite y herramientas de visualización como Plotly.

El objetivo es cargar los datos desde un archivo CSV, almacenarlos en una base de datos SQLite, y crear visualizaciones interactivas para explorar los casos confirmados por semana epidemiológica, grupo etario y departamento de residencia.

Dataset

Dataset utilizado: Casos confirmados de Dengue en Argentina (2024).
Fuente: Enlace al dataset

Cómo usar el dataset

Para que el análisis funcione, necesitas descargar el archivo casos_dengue.csv y cargarlo en Google Colab. Así es como lo haces:

Descargar el archivo:
Ve al archivo casos_dengue.csv en GitHub y descárgalo desde este enlace
.
Haz clic en "Download" para guardarlo en tu computadora.

Subir el archivo a Google Colab:
Una vez que tengas el cuaderno abierto en Colab, usa el siguiente código para cargar el archivo:

from google.colab import files
uploaded = files.upload()


Esto abrirá un cuadro de diálogo donde podrás seleccionar el archivo casos_dengue.csv desde tu computadora. Luego, solo tienes que ejecutar las celdas del cuaderno para continuar con el análisis.

Motor de Base de Datos

Motor de base de datos utilizado: SQLite.
El código para cargar los datos en la base de datos SQLite está listo y puedes usar el script para crear la base de datos de forma sencilla.

Pasos para configurar

Instala SQLite si no lo tienes.

Corre el script cargar_base_de_datos.py para crear y cargar la base de datos.

Dashboard

El dashboard interactivo utiliza Plotly para crear gráficos interactivos.

Pasos para ejecutar el código en Google Colab

Abre el notebook en Colab usando el botón de arriba.

Carga el archivo casos_dengue.csv en Google Colab.

Ejecuta las celdas para cargar los datos, limpiar los valores y generar las visualizaciones interactivas.

El código para cargar los datos en la base de datos SQLite está listo y puedes usar el script para crear la base de datos de manera sencilla.

Carga del archivo en SQLite

El código para cargar los datos en la base de datos SQLite está listo, y puedes usar el script para crear la base de datos de manera sencilla.




