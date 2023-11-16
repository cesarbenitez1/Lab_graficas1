# Lab_graficas1
Graficas 1
Supongamos que estás realizando un estudio sobre el rendimiento académico de los estudiantes en tres materias: Matemáticas, Ciencias y Literatura. Tienes los datos de las calificaciones de una muestra de estudiantes y deseas realizar un análisis visual de los resultados.

Utiliza el siguiente script para generar datos sintéticos para el análisis:
Markdown:
´´´Python
import numpy as np

rng = np.random.default_rng(42)

# Datos de calificaciones de los estudiantes
matematicas = rng.integers(50, 100, 20)
ciencias = rng.integers(40, 95, 20)
literatura = rng.integers(60, 100, 20)

# Datos de errores para el gráfico de barras de error
errores_matematicas = rng.uniform(2, 5, 2)
errores_matematicas = [min(errores_matematicas), max(errores_matematicas)]

errores_ciencias = rng.uniform(1, 4, 2)
errores_ciencias = [min(errores_ciencias), max(errores_ciencias)]

errores_literatura = rng.uniform(3, 6, 2)
errores_literatura = [min(errores_literatura), max(errores_literatura)]´´´


## Gráfico de dispersión:

Gráfico de dispersión que muestre la relación entre las calificaciones de Matemáticas y Ciencias de los estudiantes.

## Gráfico de barras de error:

Gráfico de barras de error que muestra las calificaciones promedio y sus errores correspondientes en las tres materias.

## Histograma:

Histograma que muestra la distribución de las calificaciones de Matemáticas.





