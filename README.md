Regresión Lineal Múltiple - Análisis de Calidad del Vino

Descargar archivos del proyecto

Puedes descargar los archivos desde este repositorio:

[A1_4_Vino_Tinto.ipynb
]([url](https://github.com/raulquinterog/Regresion-Vino/blob/4df0a10ecf5c00486535b66e6d83a7ec11d90658/A1_4_Vino_Tinto%20(1).ipynb)

[A1.4 Vino Tinto.csv
](https://github.com/raulquinterog/Regresion-Vino/blob/4df0a10ecf5c00486535b66e6d83a7ec11d90658/A1.4%20Vino%20Tinto.csv)

Este proyecto realiza una Regresión Lineal Múltiple para predecir la variable calidad del vino con base en distintas propiedades químicas extraídas de la base de datos Wine Quality del UCI Machine Learning Repository.

Objetivo:

Analizar los datos y construir un modelo de regresión para identificar qué variables tienen un impacto significativo en la predicción de la calidad del vino.

Estructura del Proyecto

El proyecto está organizado en un Jupyter Notebook, donde cada sección aborda un paso clave:

1️⃣ Cargar y visualizar los datos

Se importa la base de datos A1.4 Vino Tinto.csv.

Se revisan sus dimensiones y primeras filas.

2️⃣ Dividir los datos en entrenamiento y prueba

Se separan los datos en 80% para entrenamiento y 20% para prueba.

Se garantiza una partición aleatoria.

3️⃣ Ajustar el modelo de regresión lineal múltiple

Se usa sklearn.linear_model.LinearRegression para entrenar el modelo.

Se aplican métodos de selección de características:

Selección hacia adelante.

Selección hacia atrás.

Se comparan los resultados de ambas técnicas.

4️⃣ Interpretación de resultados

Se identifican las variables más importantes según sus coeficientes y contribución a la predicción.

Se analiza la significancia de cada variable en la predicción de la calidad.

5️⃣ Evaluación del modelo

Se calculan métricas de error:

R² (Coeficiente de Determinación) para evaluar el ajuste del modelo.

Comparación de R² entre selección hacia adelante y hacia atrás.

6️⃣ Visualización del ajuste del modelo

Se generan gráficas de dispersión que comparan los valores reales vs. predichos.

Se comenta sobre la calidad del modelo basado en las gráficas y los valores obtenidos.

