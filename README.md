### EVALUACIÓN FINAL MODULO 3

En este ejercicio técnico se analizan los datos de los clientes fieles de una aerolinea para entender su comportamiento.

📚 ESTRUCTURA DEL EJERCICIO

He dividido los Jupyters en 3 para hacer el código más legible:

1.Limpieza_datos: En este Jupyter estan las funciones de EDA y de limpieza, al final he creado un nuevo DataFrame con los datos ya limpios y sin nulos. 

2.Visualizacion_datos: En este Jupyter esta el EDA del csv nuevo para poder consultarlo y la visualización correspondiente con gráficos para cada pregunta del ejercicio.

--> En este destaco que he creado una variable llamada 'clientes' para agrupar todas las filas de cada cliente 'Loyalty Number' para evitar que se dupliquen datos.
En la variable he tenido en cuenta que el guardar la primera fila por cliente modificaría los datos y he creado una agregación distinta para las columnas a trabajar. Por ejemplo para 'Flights Booked' y 'Ditancia' he sumado las filas, ya que nos interesa el total. Para filas como 'Education', 'Gender' o 'Marital Status' he utilizado 'first' para solo utilizar un dato. 

VisualizaciónBONUS: En este Jupyter he realizado los ejercicios de estadística.


🛠️ HERRAMIENTAS

Lenguaje: Python
Librerías: Pandas, Numpy, Matplotlib, Seaborn, Scipy
Entorno: Jupyter Notebook

