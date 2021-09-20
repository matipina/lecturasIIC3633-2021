# Lectura 04: *Content-Based Recommendation Systems*
### IIC3633 - Sistemas Recomendadores
#### Matías Piña

En este artículo se presentan en primer lugar distintas formas de representación de elementos para sistemas recomendadores. Estos pueden ser escritos a través de múltiples atributos, incluyendo descripciones, y a partir de estos atributos se pueden generar vectores con los cuales se puede medir la similitud de distintos elementos. 

Para un sistema recomendador, se suelen crear perfiles de usuario donde se almacene cierto historial de preferencias históricas que ha tenido cada invididuo dentro del sistema. Estas preferencias pueden determinarse a través de *input* directo o indirecto por parte de los usuarios, teniendo cada una de estas opciones ventajas y desventajas. 

A partir de esto, se plantean distintas técnicas para crear sistemas recomendadores, entre las cuales a mi parecer destaca el algoritmo de Rocchio, debido a que se aleja de las técnicas tradicionales de ML.

La parte más interesante del artículo no son las explicaciones técnicas de las distintas técnicas, sino las limitaciones y extensiones planteadas al final del texto. Se afirma que ningún sistema puede dar buenas recomendaciones si no hay suficiente información, lo que hace que sea difícil recomendar textos cortos, por lo que en estos casos se recomenda usar sistemas de filtrado colaborativo. Además, presenta otras ideas de ensambles de técnicas que pueden dar muy buenos resultados.

Personalmente creo que esta idea es clave, ya que no tenemos por qué limitarnos a elegir un solo modelo si es que tenemos la posibilidad de ensamblar varios que sean complementarios, de manera que las fortalezas de uno suplan las debilidades de otro, de la misma manera en que, en el paper de Messina et. al. (2018) se propone un sistema basado una combinación de factores, algunos extraídos a partir de redes neuronales preentrenadas obteniendo *features* visuales, y otros obtenidos directamente de la metadata disponible de cada elemento, teniendo información proveniente de fuentes muy distitas, lo que les permite generar un sistema muy robusto.
