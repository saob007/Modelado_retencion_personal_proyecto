# Análisis exporatorio y contrucción de un modelo predictivo de retención del talento humano, para una empresa de Desarrollo de tecnología automotriz

## Resumen
El objetivo de este proyecto fue crear varios modelos predictivos utilizando regresión logística, bosque aleatorio (Random Forest) y arboles de decisión potenciados por gradientes (XGBoost) para predecir si un trabajador renunciaría a su cargo en una empresa del sector industrial, con intención de seleccionar el modelo que mayor "perfomance" tenga. Este proyecto utilizó un conjunto de datos recolectados por el área de Talento Humano (RR.HH.) de la empresa, durante X años. Este conjunto de datos esta comprendido por 14999 registros únicos independientes y X variables. El modelo ganador tuvo un rendimiento del X% de precisión y X% de exactitud al determinar qué características eran más importantes para separar a los pasajeros que dejaban propinas bajas de los que dejaban propinas altas. Según el modelo, la duración, la distancia y el costo del viaje fueron los factores más influyentes para determinar si un pasajero era generoso (>20%) o no generoso (<20%).

Entendimiento del negocio
Según salary.com, el salario promedio de un conductor de taxi en Nueva York es de alrededor de $45,000. Este salario es considerablemente bajo en comparación con un valor promedio de alquiler de $6,500 por mes. Es importante entender qué factores fomentan que los pasajeros dejen propinas para ayudar a los conductores a obtener un salario digno.

Entendimiento de los datos
Los datos de la Comisión de Taxis y Limusinas de Nueva York provienen de NYC.gov. Los datos consisten en aproximadamente 408,000 viajes únicos y 18 características. Las características incluyen información sobre la duración y el destino del viaje, el proveedor utilizado, información sobre peajes y tipo de pago. El gráfico a continuación muestra la distribución de cuántos pasajeros generosos (>20%) frente a no generosos existen en el conjunto de datos.

El gráfico muestra el porcentaje de pasajeros no generosos y generosos.
En relación con esto, se diseñó una característica para representar si un viaje se realizó durante las horas pico o no. Se eliminaron múltiples columnas redundantes y se reformatearon en el tipo de datos adecuado.

Modelado y Evaluación
Se utilizó un modelo de bosque aleatorio compuesto por 100 árboles de decisión para determinar la importancia de las características sobre quién dejaría una propina generosa o no. El gráfico a continuación muestra que la duración del viaje, la distancia y el costo de la tarifa fueron los tres factores más importantes para determinar si un pasajero era generoso o no generoso. El modelo en general tuvo un rendimiento del 86% de precisión y 72% de exactitud.

Gráfico de barras horizontal que muestra la importancia de las características del modelo de bosque aleatorio.

Conclusión
Este modelo puede beneficiar a los conductores de taxi al ayudarles a predecir si recibirán una propina generosa o no; sin embargo, sería útil ejecutar un modelo paramétrico para determinar cómo influirá cada variable en el monto real de la propina. En el futuro, agregar más información sobre el comportamiento de propinas pasado de los pasajeros también podría ser beneficioso para ayudar a los interesados a abordar su problema empresarial.







