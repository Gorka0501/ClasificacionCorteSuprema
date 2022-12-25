Se dispone de un dataset en inglés que contiene 3304 juicios realizados por la Corte Suprema de los Estados Unidos desde 1955 hasta 2021.
Cada juicio es una instancia del dataset y tiene 16 atributos[1], entre los cuales se consideran las siguientes:
- Los hechos del juicio, de media 200 palabras.
- Un identificador único para cada juicio.
- El tema sobre el que trata el juicio; derechos sociales, procedimientos criminales o otro campo
- Un booleano que es True si el juicio lo ganó el denunciante

El objetivo ha sido clasificar el area del cada juicio mediante el uso de clasificadores supervisados.
Se usa primero un clasificador simple, en este caso se opta po decisionTree, para luego comparar.
Después se elige el clasificador que queremos utilizar, el cual es SGDClasifier y se hace un barrido de los parámetros que se quieren observar.
A continuación se observan los resultados obtenidos del barrido y se usan para elegir los mejores según nuestro criterio.
Por ultimo se usa el clasificador con los parámetros escogidos y se recogen los resultados.
