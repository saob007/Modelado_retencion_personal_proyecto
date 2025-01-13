# Análisis exploratorio y contrucción de un modelo predictivo de retención del talento humano, para una empresa de Desarrollo de tecnología automotriz.

## Resumen
El objetivo de este proyecto fue crear varios modelos predictivos utilizando regresión logística, bosque aleatorio (Random Forest) y arboles de decisión potenciados por gradientes (XGBoost) para predecir si un trabajador renunciaría a su cargo en una empresa del sector industrial, con intención de seleccionar el modelo que mayor "perfomance" tenga. Este proyecto utilizó un conjunto de datos recolectados por el área de Talento Humano (RR.HH.) de la empresa, durante X años. El modelo ganador tuvo una rendimiento del 98,8% (accuracy), con una precisión del 98,4% (precision), una sensibilidad del 96,5% (recall), un balance del 97,4% (f1) y una discriminación del 98% (AUC) al determinar qué características eran más importantes para predecir a los empleados que dejarían la empresa de los que no. Según el modelo, la antigüedad, el nivel de satisfacción y la participación en proyectos fueron los factores más influyentes en la deserción de empleados.

## Entendimiento de la problemática del negocio
Los directivos de una empresa industrial, dedicada al desarrollo de tecnología automotríz, estan interesados en construir un modelo estadístico que permite predecir cuando un empleado abandona la empresa o no, a partir de algunos indicadores y datos que ha recodigo el área de Talento Humano para cada trabajador activo o retirado de la institución, con el objetivo de ejecutar acciones preventivas que minimicen la deserción del talento. Este interés surgió como respuesta a los resultados de una investigación interna que concluyó que el incremento en los costos operativos experimentados en los últimos 6 años se originaron por la necesidad de entrenamiento de nuevos empleados, perdidas materiales en el área como consecuencia de una baja adaptabilidad a los procedimientos operativos y la poca eficiencia de los procesos.

## Entendimiento de los datos
El conjunto de datos aportados por la empresa industrial está comprendido por 14999 registros únicos e independientes y 10 características. Las características o variables incluyen información sobre el nivel de satisfacción comunicado por el trabajador, el nivel de desempeño calculado por el área al que pertenece, el número de proyectos en los que ha participado el trabajador, el promedio de horas mensuales trabajadas, la antigüedad del empleado, las promociones de cargo, el nivel salarial, el área o departamento al que pertenece, si ha sufrido accidentes laborales y si se el trabajador se encuentra activo o retirado de la empresa.
El gráfico a continuación muestra  la distribución de cuantos empleados activos y retirados existen en el conjunto de datos.

<img src="assets/img/img1.png" alt="Distribución de datos" 
     style="display: block; margin: auto; max-width: 50%; height: auto;">

Como parte de la preparación para modelado de los datos, se eliminaron columnas innecesarias, se verificaron valores nulos y registros duplicados, se gestionaron valores atípicos y se formatearon en el tipo de datos adecuado.

## Modelado y Evaluación

Se utilizó un modelo de bosque aleatorio compuesto por 100 árboles de decisión para determinar la importancia de las características sobre quién dejaría una propina generosa o no. El gráfico a continuación muestra que la duración del viaje, la distancia y el costo de la tarifa fueron los tres factores más importantes para determinar si un pasajero era generoso o no generoso. El modelo en general tuvo un rendimiento del 86% de precisión y 72% de exactitud.

Gráfico de barras horizontal que muestra la importancia de las características del modelo de bosque aleatorio.

Conclusión
Este modelo puede beneficiar a los conductores de taxi al ayudarles a predecir si recibirán una propina generosa o no; sin embargo, sería útil ejecutar un modelo paramétrico para determinar cómo influirá cada variable en el monto real de la propina. En el futuro, agregar más información sobre el comportamiento de propinas pasado de los pasajeros también podría ser beneficioso para ayudar a los interesados a abordar su problema empresarial.







