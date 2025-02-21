# Práctica 13-17: 

Elaboró: Carlos Alejandro Jarero Gonzalez <al255813@alumnos.uacj.mx>

Matrícula: 255813

El presente Notebook fue relizado en equipo local con Kernel Python 3.11.8 en VS Code.

## Objetivos

El objetivo de esta actividad es que los estudiantes practiquen los temas vistos de carga de datos, normalización de nombres de columnas, separación y unión de columnas, errores en los tipos de datos. Todo es en un conjunto de datos utilizando Pandas en Python.


## Instrucciones de uso

Este notebook puede extraer datos del archivo ```miaad-nyc-r-s.csv```, para analizar la información presente.

Si quieres cambiar el archivo, o la dirección del mismo, solo ve a la sección de parameters y cambia el ```input_path```.

### Si usas Google Colab

1. Ve a la sección de Files y asegurate de tener habilitado el acceso a tu Google Drive, de lo contrario hablitalo y dale los permisos correspondientes.
2. Si ya has realizado el paso anterior verás en tu notebook la siguiente instrucción de python para montar un volumen en el caso de linux ```/content/drive```, esto puede cambiar en diferentes sistemas operativos.
![Drive Mounting](./assets/DriveMount.png)
3. Asegurate de ejecutar la sección previa, dependidendo si ya has dado o no los permisos en este paso puede que de nuevo te solicite darle permiso. 
4. Ahora verás um directorio llamado drive donde encontarás tu Drive, ahí sube el archvio a procesar.
5. Copia el path absoluto de archivo de ```miaad-nyc-r-s.csv``` en ```input_path```.

## Instrucciones

1. Descarga el archivo CSV, ```miaad-nyc-r-s.csv```, proporcionado en esta tarea. También lo puedes encontrar en recursos.
2. Crea un notebook en colab y guarda el archivo csv descargado en tu drive.
3. Agrega secciones en el colab poniendo como título el nombre de la práctica.

### Práctica 13: Carga de Datos

Al final del archivo contiene una línea que dice "Esta es una línea que no deberías cargar". Esta línea es irrelevante por lo tanto al cargar el CSV a un dataframe se debería de ignorar.

- Carga el archivo a un dataframe usando el código necesario para omitir la última fila.
- Usa ```df.tail(3)``` para demostrar que no has cargado la última línea.
- Imprime la cantidad de filas y columnas del dataframe.

### Práctica 14: Agregar una columna

- Imprime los nombres de la columnas del archivo.
- Asegúrate que el nombre de la primera columna debería ser INDEX MIIAD. Si esto no es así, entonces agrega dicho nombre a la columna y vuelve a imprimir los nombres para mostrar el cambio realizado.

### Práctica 15: Normalización de los nombres de la columna

- Normaliza los nombres de ls columnas, los cuales deberán estar en minúsculas. Asimismo, reemplaza los espacios con guion bajo.
- Imprime los nombres de las columnas para demostrar que has realizado la normalización.

### Práctica 16: Errores en los Tipos de Datos

- Imprime los tipos de datos de cada columna.
- Asegúrate que las columnas de SALE PRICE(sale_price), LAND SQUARE FEET (land_square_feet), GROSS SQUARE FEET (gross_square_feet) sean de tipo flotante. Escribe qué tipo de dato tienen asignado. Si no son correctos, realiza el cambio.
- Imprime de nuevo los tipos de datos para demostrar que has arreglado el problema.

### Práctica 17: Genera el diccionario de datos del dataframe preprocesado. Imprime el contenido de dicho diccionario
