# Descripción 
Este análisis se centra en el estudio de datos de tráfico en la M30 de Madrid mediante el uso de series temporales. El conjunto de datos proviene de lecturas realizadas en puntos específicos a lo largo de la M30, con variables como intensidad (flujo de tráfico), velocidad media (vmed), entre otras. El objetivo es realizar un análisis exploratorio y comparativo de patrones de tráfico en diferentes días y momentos del día.

## Preprocesamiento de Datos
* Se realiza un filtrado adicional para eliminar puntos de medida que no cuentan con la serie temporal completa de 2880 puntos (equivalente a 30 días de recolección de datos con intervalos de 15 minutos). Esto se hace para facilitar el análisis y mantener la consistencia en los datos.

## Visualización y Análisis
* Se utilizan gráficos interactivos con Altair para visualizar la intensidad y velocidad media del tráfico en diferentes puntos de medida a lo largo del tiempo. Se destacan patrones temporales, como la variación horaria y las diferencias entre días de la semana.

## Análisis Comparativo
* Se formula una hipótesis sobre la diferencia en los patrones horarios de congestión del tráfico entre distintos días de la semana. Se agrupan los datos por día y hora, calculando las medias de intensidad y velocidad media. Se visualizan estas medias mediante gráficos de líneas y se observan diferencias notables entre días laborables y fines de semana.

## Métricas y Comparación de Días
* Se utilizan métricas como el Mean Squared Error (MSE) para cuantificar las diferencias en la intensidad del tráfico entre diferentes días de la semana. Se visualizan las diferencias a través de un heatmap.

## Conclusiones
* El análisis proporciona insights sobre los patrones de tráfico en la M30 de Madrid, destacando variaciones horarias y diferencias entre días de la semana. Estas observaciones podrían ser útiles para la planificación de infraestructuras viales y la gestión del tráfico en la ciudad.
