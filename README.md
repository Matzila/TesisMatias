# TesisMatias

## Scripts utilizados para el caso práctico

##### Tweet crawler: Este script es utilizado para la descarga de tweets, con la palabra clave en la variable “Brand”. Este archivo representa la descarga de tweets del candidato Espert.

##### Parseo y conversión a CSV: Los tweets descargados en el script anterior son convertidos para adaptarlos a MongoDB.

##### Taggeo de tweets: Los tweets en MongoDB son recuperados y mostrados, según candidato, para realizar la clasificación manual. Estos tweets se clasifican por candidato y almacenados nuevamente en la base.

##### Análisis de los tweets: Los tweets previamente clasificados y almacenados en MongoDB son obtenidos, separados en conjunto de datos de entrenamiento y de prueba y entregados a los modelos. Estos aprenden y prueban la clasificación. Los resultados son la exactitud de clasificación de los tweets de prueba, en términos porcentuales.

##### Nube de palabras: Este script permite la construcción de una nube de palabras por candidato, modificando el parámetro de palabra clave. Las mismas son graficadas sobre imágenes representativas según el candidato. No se detalla la construcción de las nubes, porque están fuera del alcance de la tesis.
