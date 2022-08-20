# Parcial 1 - Solución.

## Punto 1: ¿Qué tipo de variables tiene el dataset? Detalle el tipo de variable de cada columna.
A partir del perfilamiento de datos y de la función estudiantes_df.dtypes, se pueden determinar los siguientes tipos de variables: <br>
gender                          object / varible cualitativa o categórica nominal <br>
race/ethnicity                  object / varible cualitativa o categórica nominal <br>
parental level of education     object / varible cualitativa o categórica ordinal <br>
lunch                           object / varible cualitativa o categórica binaria <br>
test preparation course         object / varible cualitativa o categórica binaria <br>
math score                     float64 / varible cuantitativa continua <br>
reading score                  float64 / varible cuantitativa continua <br>
writing score                  float64 / varible cuantitativa continua <br>

## Punto 2: ¿Qué tipo de problemas de calidad de datos logra identificar? Defina e implemente las estrategias de limpieza de datos que correspondan.
A partir del perfilamiento de datos se puede inferir que el mayor problema de calidad de datos son los campos nulos (missing values). El caso más crítico se encuentra en la variable 'parental level of education', en donde el porcentaje de missing values alcanza un 6% con respecto al total de observaciones. En general, el dataset presenta una buena calidad en la estructura de sus datos: no se observan variables mal clasificadas en su tipo de dato, formatos incorrectos y tampoco se observan que los labels mal escritos en las variables categóricas. No se recomienda eliminar los campos vacios ya que no se presentan en la misma observación.

## Punto 3: ¿En qué asignatura en promedio los estudiantes obtuvieron un mejor puntaje? ¿Hay evidencia de algún sesgo en la distribución de dichos puntajes?
En promedio los estudiantes obtuvieron un mejor puntaje en la asignatura de lectura. <br>
A partir de las gráficas, se puede determinar que las distribuciones de los 3 puntajes presentan una ligera asimetría negativa. En consecuencia, si hay evidencia de sesgo pero éste no es significativo.

## Punto 4: ¿Existe alguna correlación entre los puntajes obtenidos en las tres asignaturas?
Sí, los 3 puntajes están altamente correlacionados. En especial, los puntajes que presentan mayor correlación son 'writing score' y 'reading score'.

## Punto 5. ¿Hay alguna diferencia observable en los puntajes de la asignatura de matemáticas entre géneros? ¿Qué género obtuvo en promedio los mejores puntajes?
No hay ninguna diferencia observable en los puntajes de la asignatura de matemáticas entre géneros. <br>
El género masculino obtuvo en promedio los mejores puntajes de la asignatura de matemáticas.

## Punto 6. ¿Qué nivel de escolaridad tienen los padres de los estudiantes que obtuvieron un puntaje por encima del percentil 85 en la asignatura de escritura? ¿Cómo se distribuye la escolaridad entre esta población?
Se presentan los siguientes niveles de escolaridad con sus respectivos porcentajes: <br>
associate's degree    24.62% <br>
some college          22.31% <br>
bachelor's degree     17.69% <br>
master's degree       12.31% <br>
some high school      11.54% <br>
high school            5.38% <br>

## Punto 7. ¿Qué porcentaje de los estudiantes obtuvieron puntajes iguales o superiores a 90 en las tres asignaturas? De estos estudiantes, ¿que porcentaje estudió para los exámenes?
Solo el 1.9% de los estudiantes obtuvieron puntajes iguales o superiores a 90 en las tres asignaturas. <br>
El 52.63% de los estudiantes que obtuvieron puntajes iguales o superiores a 90 en las tres asignaturas estudió para los exámenes.
