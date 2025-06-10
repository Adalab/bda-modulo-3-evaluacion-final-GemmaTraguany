✈️ EVALUACIÓN FINAL MODULO 3

En este ejercicio técnico se analizan los datos de los clientes fieles de una aerolinea para entender su comportamiento.

📚 ESTRUCTURA DEL EJERCICIO

He dividido los Jupyters en 3 para hacer el código más legible:

  1.Limpieza_datos: En este Jupyter estan las funciones de EDA y de limpieza, al final he creado un nuevo DataFrame con los datos ya limpios y sin nulos. 
  
  2.Visualizacion_datos: En este Jupyter esta el EDA del csv nuevo para poder consultarlo y la visualización correspondiente con gráficos para cada pregunta del ejercicio.
  
    🧠 Nota destacada: 
    Se ha creado una variable llamada clientes para agrupar la información por cliente único (Loyalty Number), evitando duplicados.
    Para ello, se utilizaron estrategias de agregación específicas:
      
    Columnas acumulativas (como 'Flights Booked' y 'Distance') → se aplicó .sum().
    Columnas categóricas (como 'Education', 'Gender' o 'Marital Status') → se aplicó .first() para conservar un valor rep

  3.VisualizaciónBONUS: En este Jupyter he realizado los ejercicios de estadística.


🛠️ HERRAMIENTAS

  Lenguaje: Python  
  Entorno: Jupyter Notebook
  Librerías: 
      - Pandas para manipulación de datos
      - NumPy para operaciones numéricas
      - Matplotlib y Seaborn para visualización
      - Scipy para análisis estadístico


