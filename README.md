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


----------------------------------------------------------------

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

--------------------------------------------------------------
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
Esto abrirá un cuadro de diálogo donde podrás seleccionar el archivo casos_dengue.csv desde tu computadora. Después de cargarlo, podrás continuar con el análisis ejecutando las celdas en el cuaderno de Colab.

Motor de Base de Datos
Motor de base de datos utilizado: SQLite.

SQLite es un sistema de gestión de bases de datos ligero, que almacena la base de datos en un solo archivo, sin necesidad de un servidor externo. En este proyecto, SQLite se usa para almacenar los datos de los casos confirmados de Dengue.

Instrucciones para configurar SQLite:
En Google Colab:
SQLite ya está preinstalado, por lo que no necesitas hacer nada adicional. Solo necesitas cargar el archivo CSV y ejecutar el código.

En tu máquina local:
Si estás trabajando localmente, asegúrate de tener SQLite instalado. Puedes hacerlo fácilmente con el siguiente comando:

bash
Copiar código
pip install sqlite3
Cargar los datos en SQLite:
Para cargar los datos del archivo casos_dengue.csv en la base de datos SQLite, ejecuta el script cargar_base_de_datos.py. Este script creará la base de datos y cargará la información en la tabla correspondiente.

Si no tienes el script o deseas crearlo, asegúrate de seguir el siguiente patrón para cargar los datos desde el CSV a SQLite:

python
Copiar código
import sqlite3
import pandas as pd

# Conectar a la base de datos (se crea un archivo .db si no existe)
conn = sqlite3.connect('dengue_cases.db')
cursor = conn.cursor()

# Crear la tabla (si no existe)
cursor.execute('''
CREATE TABLE IF NOT EXISTS casos_dengue (
    semana_epidemiologica INTEGER,
    grupo_etario TEXT,
    departamento TEXT,
    casos_confirmados INTEGER
)
''')

# Leer el archivo CSV
df = pd.read_csv('casos_dengue.csv')

# Insertar los datos en la base de datos
df.to_sql('casos_dengue', conn, if_exists='replace', index=False)

conn.commit()
conn.close()
Este script crea una base de datos SQLite llamada dengue_cases.db y carga los datos del CSV en la tabla casos_dengue.

Dashboard
El dashboard interactivo utiliza Plotly para crear gráficos interactivos.

Visualizaciones disponibles:
Semana epidemiológica

Grupo etario

Departamento de residencia

Pasos para ejecutar el código en Google Colab
Abre el notebook en Colab usando el botón de arriba.

Carga el archivo casos_dengue.csv en Google Colab.

Ejecuta las celdas para cargar los datos, limpiar los valores y generar las visualizaciones interactivas con Plotly.

Clonar el repositorio
Puedes clonar este repositorio en tu máquina local con el siguiente comando:

bash
Copiar código
git clone https://github.com/cristianccr/analisis-casos-dengue.git
Requisitos
Si estás ejecutando el proyecto localmente, asegúrate de tener todas las bibliotecas necesarias. Para instalar las dependencias, crea un archivo requirements.txt con el siguiente contenido:

nginx
Copiar código
pandas
plotly
sqlite3
Luego, instala las dependencias con:

bash
Copiar código
pip install -r requirements.txt
Contribuir
Si deseas contribuir a este proyecto, puedes hacer un fork de este repositorio y enviar un pull request con tus cambios.

URL del repositorio
Este repositorio contiene todos los archivos necesarios para ejecutar el análisis. Puedes encontrar el código fuente en el siguiente enlace:

https://github.com/cristianccr/analisis-casos-dengue
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






