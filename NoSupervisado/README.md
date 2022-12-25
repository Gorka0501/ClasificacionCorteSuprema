Se dispone de un dataset en inglés que contiene 3304 juicios realizados por la Corte Suprema de los Estados Unidos desde 1955 hasta 2021.
Cada juicio es una instancia del dataset y tiene 16 atributos[1], entre los cuales se consideran las siguientes:
- Los hechos del juicio, de media 200 palabras.
- Un identificador único para cada juicio.
- El tema sobre el que trata el juicio; derechos sociales, procedimientos criminales o otro campo
- Un booleano que es True si el juicio lo ganó el denunciante

El primer objetivo ha sido conseguir agrupar todas las instancias en diferentes clústeres
según los tópicos a los que pertenecen tras analizar los hechos de cada juicio. De esta forma, cada
hecho puede pertenecer a un sólo tópico (muy poco probable) con una probabilidad de 1 sobre 1
o puede tener distintas probabilidades de pertenecer a más de un tópico.

