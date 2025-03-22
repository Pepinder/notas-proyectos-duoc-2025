# Introducción a la mineria de datos

La definición más aceptada de mineria de datos (`data mining`) es el descubrimiento de `modelos` para los datos. Sin embargo, estos `modelos` pueden tomar diversas formas, dependiendo del enfoque utilizado. A continuación se presentan las principales modelos de mineria de datos.

1. **Modelado Estadístico**

   - Originalmente, el término "minería de datos" tenía una connotación negativa, refiriendose a la extracción de información no respaldada por los datos.
   - Hoy en día, e ve de manera positiva como la construcción de modelos estadísticos que describen la distribución subyacente de los datos.
   - Ejemplo: Ajustar una distribución gaussiana a un conjunto de datos estimando su media y desviación estándar.

2. **Machine Learning**

   - A menudo considerado sinónimo de minería de datos, el aprendizaje automático utiliza algoritmos para entrenar modelos con datos.
   - Algoritmos comunes incluyen redes bayesianas, máquinas de vectores de soporte, árboles de decisión y modelos ocultos de Markov.
   - Efectivo cuando el objetivo no está claro (por ejemplo, predecir preferencias de películas en el desafío de Netflix).
   - Menos efectivo cuando el objetivo está bien definido (por ejemplo, identificar currículos en la web).

3. **Enfoques computacionales**

   - Se centra en soluciones algorítmicas para extraer insights de los datos.
   - Los modelos pueden ser resúmenes (por ejemplo, promedio, desviación estándar) o características extraídas (por ejemplo, conjuntos de ítems frecuentes, ítems similares).

4. **Resumen de datos**

   - Resumir los datos de manera sucinta es un aspecto clave de la minería de datos.
   - Ejemplos:
     - **PageRank**: Resume la importancia de una página web basándose en probabilidades de caminata aleatoria.
     - **Clustering**: Agrupa puntos de datos similares (por ejemplo, el análisis de John Snow sobre el brote de cólera).

5. **Extracción de características**

   - Identifica las características o patrones más significativos en los datos.
   - Ejemplos:
     - **Conjuntos de Ítems Frecuentes**: Encuentra ítems que suelen aparecer juntos (por ejemplo, análisis de canastas de mercado).
     - **Ítems Similares:** Identifica conjuntos similares (por ejemplo, filtrado colaborativo para recomendaciones).

6. **Límites estadísticos en la minería de datos**

   - **Principio de Bonferroni**: Advierte sobre la sobreinterpretación de patrones en grandes conjuntos de datos.
     - En datos aleatorios, eventos raros ocurrirán por casualidad, lo que lleva a falsos positivos.
     - Ejemplo: Buscar "malhechores" en registros de hoteles genera muchos falsos positivos, haciendo la tarea poco práctica.
