---
layout: default
title: Resultados
description: rellenar
---

A partir del análisis de los datos, y en específico el modelo entrenado de regresión lineal, fue posible encontrar cierta influencia que ejercen los ingresos del hogar y las redes de internet fijas en el ámbito académico. Si bien existe una gran similitud entre el porcentaje de alumnos aprobados, el promedio con el que pasan de curso y la región en la que se encuentran, al aplicar regresión lineal para intentar predecir el rendimiento de un estudiante se puede notar que ambas variables le afectan considerablemente.

Teniendo esta afirmación como base para el resto de las conclusiones, es relevante mencionar las preguntas planteadas al inicio del proyecto, y revisitarlas de forma que puedan responderse o modificarse acorde a lo que todo el proyecto ha demostrado:
hay que subirlo al repositorio ;;
* ¿Cuáles son las regiones que presentan mayor desempeño académico y cuáles son las diferencias con las que tienen peor rendimiento? ¿Coincide lo anterior con el ingreso que estas presentan?

Las regiones con mejor desempeño académico son la región de Magallanes y la región de Aysén, mientras que las de peor rendimiento son las regiones de O'Higgins y Los Lagos. En comparación a los datos económicos que estas regiones presentan, la única región que es además una en la que las personas tienen mayores ingresos es la de Magallanes.

* ¿Se puede decir que hay una relación lineal entre ambas variables?

Si bien existen ciertas similitudes en cuanto a los bienes y el rendimiento, no es posible decir que tienen una relación estrictamente lineal. Un ejemplo de esto es la región de Tarapacá, que a pesar de estar entre las de peor desempeño, es de las que más ingresos tiene. 

* ¿Se puede afirmar que el acceso a internet y los ingresos económicos influyen en los estudiantes?

Ya hemos dicho que la relación entre variables no es tan simple como parecería ser, pero aun así se puede observar una gran influencia entre ellas, como se pudo apreciar en los gráficos de los coeficientes de la regresión lineal, el ingreso económico tenia un gran efecto en la predicción final. De todas formas, es bastante probable que de todos las variables que han afectado a los estudiantes durante estos años, estos sean de los más notorios. Cabe mencionar, además, que a lo largo del análisis se hizo notoria la variable de asistencia, (cantidad de veces que el alumnado estaba en sus clases), pudiendose ver que esta era un factor importante al momento de predecir en el desempeño del estudiante.
* ¿Existe alguna conexión además entre el acceso a internet y los ingresos económicos?

Existen ciertas coincidencias entre las regiones con más ingresos y la cantidad de redes fijas disponibles, como la Región Metropolinana, pero al existir regiones como la de Aysén que tiene buenos ingresos y pocas redes, no se puede afirmar con certeza que estén vinculadas.

* ¿Se puede predecir el desempeño del próximo año a partir de lo observado?

El modelo final podria ser utilizado como guia para armar ciertas expectactivas respecto al rendimiento del año siguiente, pero como señalan las metricas de error, las predicciones no son del todo exactas, por lo que en el caso de que se necesiten resultados certeros, deberia de entrenarse un modelo nuevo con una mayor cantidad de variables predictoras, o con un grupo de variables distinto al usado en este proyecto. 

Una posible forma de mejorar el rendimiento del modelo podria ser utilizar el equivalente de las variables predictoras utilizadas en este trabajo, enfocandose en las comunas y no en la región, pues datos generados a partir de esta última son por naturaleza, menos especificos que los comunales.

