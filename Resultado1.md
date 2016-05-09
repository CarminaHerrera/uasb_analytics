#Resumen 1

##Objetivo 
Se desea conocer los factores que afectan en el rendimiento de los estudiantes segun los datos: 

* Calificacion final de curso 
* Consumo de alcohol diario 
* Consumo de alcohol en fin de semana
* Tiempo libre 
* Salida con  amigos 
* Ausencias

##Proceso
Para el estudio se ha utilizado el algortimo de K-means que es uno de los esquemas más simples de clustering  que se aplica al conjunto de datos antes mencionado
 

Se agrega el el operador Retrieve con el Dataset EstudiantesMatemáticas del Repositorio local, Se agrega el selector de atributos que son el conjunto de datos utilizados para la predicción, se agrega el Clustering de modelado K-means como clasificador con el parámetro K 4 agrupaciones y 1 como número de grupos especificados, se conecto el parametro de salida para escribir un archivo write.csv. 

##Aplicacion
Se ejecuto el algoritmo: 
K= 4 
iteraciones = 10

## Gráfico del hallazgo 1

1. Rendimiento de Estudiantes

![Rendimiento de Estudiantes](https://github.com/CarminaHerrera/uasb_analytics/blob/master/Resultado1.png "Rendimiento de Estudiantes")
![Rendimiento de Estudiantes](https://github.com/CarminaHerrera/uasb_analytics/blob/master/Resultado1.1.png "Rendimiento de Estudiantes")

##Conclusion

En el modelo se pudo observar que el rendimiento de los estudiantes baja mientras más es el consumo de alcohol en la semana y debido a la ausencia de los estudiantes. 
* Se pude concluir que en el cluster 3 se encuentra el mayor porcentaje de ausencia de los estudiantes. y le sigue el cluster 1. 
* Los estudiantes una salud regular se encuntran en los 4 clusters analizados.
* Los estudiantes con mejores calificaciones se encuntran en el Cluster 2. 


* Cluster Model *
 * Cluster 0: 50 items
 * Cluster 1: 78 items
 * Cluster 2: 262 items
 * Cluster 3: 5 items
**Total number of items: 395**

