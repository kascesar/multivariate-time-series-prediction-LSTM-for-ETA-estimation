#  Estimacion de ETA basado en redes neuronales LSTM
---
Las estimaciones de completitud tempral de ciertas tareas es un area de mucho interes de estudio debido a su potenciabilidad industrial en diversas areas.

En este trabajo se muestra un metodo para calcular el 'Tiempo estimado de arribo', por sus siglas en ingles "ETA", estudiando una muestra temprola del un movil en un circuito con registros de "GPS".
Para conseguir esto se diseno una red neuronal basada en el concepto de memoria a largo-corto plazo (por sus siglas en ingles LSTM).

se hazo un tratamiento muy simple a estos datos que estan en en un formato ".csv", se crearan variables apartir de los datos que ya tenemos, debido a la causalidad que se penso para ellos en cuanto al calculo.

Luego se hace un analisis de los datos y resultados frente al metodo presentado aqui.


## indice



1.   Estudiando el data set
2.   preparacion del data set, creacion de la red neuronal y entrenamiento 
3.   Analisis de resultados
4.   conclusion
