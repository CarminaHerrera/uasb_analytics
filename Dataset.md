#Dataset de Rendimiento de Estudiantes 

##Descripcion
Este Dataset es un enfoque de los estudiantes en la educación secundaria de datos de dos escuelas portuguesas. Los atributos de datos incluyen las calificaciones del estudiante, características, relacionadas sociales y demográficas de la escuela) y se recogieron mediante el uso de informes de la escuela y cuestionarios. Dos conjuntos de datos se proporcionan con respecto al rendimiento en: Matemáticas (MAT). En [Cortés y Silva, 2008], los dos conjuntos de datos se modelaron en virtud de las tareas de clasificación y regresión binaria / de cinco niveles. Nota importante: el objetivo atribuir G3 tiene una fuerte correlación con los atributos G2 y G1. Esto se debe a que G3 es el grado de último año (emitida en el 3er periodo), mientras que G1 y G2 corresponden a la 1ª y 2ª grados. Es más difícil de predecir sin G3 G2 y G1, pero tal predicción es mucho más útil.


##Objetivo
	El uso de minería de datos para  predecir el rendimiento del estudiante en la educación secundaria.

##Características 

* Características del Conjunto de datos: multivariante
* Número de instancias: 649
* Zona: Social
*Características del producto Características: Entero
* Fecha DataSet: 7/11/2014
Las tareas asociadas:
Clasificación, regresión


#* Atributos para el estudiante de la clase de Matemáticas, conjuntos de datos:*

1. school - Escuela del estudiante (tipo binario: "GP" - Gabriel Pereira o "MS" - Mousinho da Silveira) 
2. sex - Sexo del estudiante (tipobinario: "F" - femenino o "M" - masculino)
3. age - Edad del estudiante (tipo numérico: del 15 al 22)
4. address - Dirección particular del estudiante (tipo binario: "U" - urbana o "R" - rural)
5. famsize - Tamaño de la familia (tipo binario: "LE3" - menor o igual a 3 o "GT3" - mayor que 3)
6. Pstatus - Situación de convivencia de los padres ( tipo binario: "T" - que viven juntas o "A" - aparte)
7. Medu - Educación de la madre (tipo numérico: 0 - ninguno, 1 - educación primaria (4º grado), 2 - 5 al 9 grado, 3 - educación secundaria o 4 - la educación superior)
8. Fedu - Educación del padre (tipo numérico: 0 - ninguno, 1 - educación primaria (4º grado), 2 - 5 al 9 grado, 3 - educación secundaria o 4 - la educación superior)
9. Mjob - Trabajo de la madre (tipo nominal: "maestro", la atención de "salud" relacionados, "servicios" civiles (por ejemplo, administrativo o policial), "en_casa" u "otra")
10. Fjob - Trabajo del padre (tipo nominal: "maestro", la atención de "salud", "servicios relacionados" civiles (por ejemplo, administrativo o policial), "en_casa" u "otra")
11. reason - Razón para elegir la escuela (tipo nominal: cerca de "casa", la escuela "reputación", la preferencia "por supuesto" u "otra")
12. guardian - Tutor del estudiante (tipo nominal: "madre", "padre" o "otro")
13. traveltime - Tiempo de viaje del hogar a la escuela (tipo numérico: 1 - <... 15 min 2 - 15 a 30 min, 3 - 30 minutos a 1 hora, o 4 -> 1 hora)
14. studytime - Tiempo de estudio semanal (tipo numérico: 1 - <2 horas, 2 - 2 a 5 horas, 3-5 a 10 horas, o 4 -> 10 horas)
15. failures - Número de fracasos del pasado (clase numérica: n si 1 <= n <3, 4 persona)
16. schoolsup - Ayuda educativa adicional (tipo binaria: sí o no)
17. famsup - Apoyo educativo familiar (tipo binaria: sí o no)
18. paid - clases adicionales pagadas dentro del de la materia (matemáticas) (tipo binaria: sí o no)
19. activities- Actividades extra-curriculares (tipo binaria: sí o no)
20. nursery - Guardería (tipo binaria: sí o no)
21. higher - quiere tomar la educación superior (tipo binaria: sí o no)
22. Internet - Acceso a Internet en casa (tipo binaria: sí o no)
23. romantic - con una relación romántica (tipo binaria: sí o no)
24. famrel - la calidad de las relaciones familiares (tipo numéricos: a partir del 1 - muy malo a 5 - excelente)
25. freetime - tiempo libre después de la escuela (tipo numérico: a partir de 1 - muy baja a 5 - muy alto)
26. goout - Salir con los amigos (numérico: a partir de 1 - muy baja a 5 - muy alto)
27. dALc - Jornada laboral consumo de alcohol (tipo numérico: a partir de 1 - muy baja a 5 - muy alto)
28. Walc - Fin de semana el consumo de alcohol (tipo numérico: a partir de 1 - muy baja a 5 - muy alto)
29. health - Estado de salud actual (tipo numérico: a partir de 1 - muy malo, 5 - muy bien)
30. absences - Número de ausencias escolares (tipo numérico: de 0 a 93)


Estos grados están relacionados con el sujeto supuesto, Matemáticas:

31. G1 - Calificacion del primer periodo del año (numérico: de 0 a 20)
31. G2 - Calificacion del segundo periodo del año (numérico: de 0 a 20)
32. G3 - Calificación final (numérico: de 0 a 20, el objetivo de producción)

