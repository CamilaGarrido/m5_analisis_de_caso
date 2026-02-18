Análisis de Gasto Semanal - DataNova 
Este proyecto forma parte de un análisis de consultoría para una cadena de supermercados interesada en entender el comportamiento de gasto de sus clientes frecuentes.

Descripción del Caso
El objetivo principal es estimar el gasto medio semanal poblacional mediante técnicas de inferencia estadística. Se trabajó con una muestra aleatoria de 60 clientes.

Datos de la Muestra:
Tamaño de muestra (n): 60 clientes.
Gasto medio semanal ( x ): 132.50 USD.
Desviación estándar muestral (s): 15.40 USD.
Nivel de confianza: 95%.

Metodología y Distribución
Se seleccionó la distribución t-Student para la construcción del intervalo de confianza.
Justificación: La desviación estándar poblacional es desconocida, por lo que se utiliza la desviación estándar de la muestra como estimador.

Grados de Libertad: 59 (n−1).

La fórmula utilizada es:
IC= x̄ ± tα/2 ⋅ s/√n


​
Resultados e Interpretación

El análisis, desarrollado en Python, arrojó un intervalo de confianza al 95% de [128.52 USD - 136.48 USD].
Interpretación: Existe un 95% de confianza en que el gasto promedio de todos los clientes frecuentes de la cadena se encuentra dentro de este rango.
Comparación (Plus +): Se incluyó un cálculo al 99% de confianza para analizar cómo la precisión disminuye al aumentar la certeza del intervalo.

Recomendaciones para la Gerencia

Basado en estos hallazgos, se recomienda a la cadena de supermercados:
Fijación de Umbrales: Diseñar programas de recompensas con un ticket mínimo cercano a 128 USD, asegurando que sean alcanzables para el promedio real de clientes.
Proyecciones: Utilizar el límite inferior de 128.52 USD para estimaciones conservadoras de flujo de caja semanal.
