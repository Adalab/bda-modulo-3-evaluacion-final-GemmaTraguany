📚 Estructura del Ejercicio
He dividido los notebooks en 3 partes para hacer el código más legible:

1. Limpieza_datos.ipynb
Contiene funciones para el análisis exploratorio de datos (EDA) y limpieza.
Al final se genera un nuevo DataFrame con los datos limpios y sin valores nulos.

2. Visualizacion_datos.ipynb
Incluye el EDA del nuevo CSV limpio y la visualización correspondiente, con gráficos que responden a cada pregunta del ejercicio.

    🧠 Nota destacada:
    Se ha creado una variable llamada clientes para agrupar la información por cliente único (Loyalty Number), evitando duplicados.
    Se usaron estrategias de agregación específicas:
    
    Columnas acumulativas (como Flights Booked y Distance) → .sum()
    
    Columnas categóricas (como Education, Gender, Marital Status) → .first() para conservar un valor representativo

3. VisualizaciónBONUS.ipynb
Contiene los ejercicios de estadística adicionales.

🛠️ Herramientas
Lenguaje: Python
Entorno: Jupyter Notebook
Librerías:
  pandas → manipulación de datos
  numpy → operaciones numéricas
  matplotlib, seaborn → visualización de datos
  scipy → análisis estadístico


