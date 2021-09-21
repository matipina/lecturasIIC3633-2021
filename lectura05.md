# Lectura 05: *Context-Aware Recommender Systems*
### IIC3633 - Sistemas Recomendadores
#### Matías Piña

En este artículo se presenta un tipo de sistema recomendador que, a diferencia de los tradicionales vistos hasta ahora, no solo toma en consideración las interacciones de los usuarios con los distintos ítems, sino que también considera el contexto en el cual estas itneracciones son realizadas. 

El paper parte explicando qué significa contexto, y se hace mucho énfasis en cómo la definición de este concepto va a variar dependiendo de la disciplina en la cual se esté utilizando. A grandes rasgos, se explica que la definición de contexto puede abarcar factores muy variados, como eventos específicos que puedan haber ocurrido en la vida de una persona, o elementos como la ubicación espacial y temporal de alguien en un momento determinado. Incluso puede considerar condiciones climáticas y de temperatura. Se terminan definiendo tres dimensiones en las cuales se suele dividir el contexto: temporal, espacial y tecnológica.

Luego se menciona que esta información puede ser almacenada dividiéndola en dimensiones dependiendo del tipo de datos y de su estructura, y cada dimensión estará definida a su vez por un set de múltiples atributos. Acá, me parece especialmente interesante y valiosa la representación gráfica en forma de un cubo tridimensional que se realiza para explicar la estructura de estos datos y cómo se relacionarían, por ejemplo, usuarios e ítems en función del tiempo, siendo cada uno de estos elementos representado con una dimensión, ya que permite explicar fácilmente un concepto que en teoría suena complejo, lo cual es justamente uno de los desafíos de los modelos predictivos de todo tipo: mejorar su explicabilidad.

A continuación el paper menciona distintas maneras de obtener esta información contextual, para finalmente explicar distintos paradigmas con los cuales podemos inorporar esta información nueva a los modelos recomendadores que ya conocemos. Acá, me parece importante destacar que no solo explican los paradigmas por si mismos, sino que  también se exponen combinaciones de estos par lograr sistemas más robustos, lo cual me parece clave, ya que en aplicaciones reales siempre intentaremos construir modelos robustos y no necesariamente nos limitaremos a un único paradigma.

Por último, me parece destacable que se mencionen los obstáculos que se presentan en la aplicación de estos sistemas, especialmente la mención de la necesidad de construir buenas interfaces de usuario para que la interacción con los sistemas sea más intuitiva y sencilla, ya que el lado de *frontend* suele verse muy distante cuando se discute sobre modelos predictivos y *machine learning*, pero es importante tener en cuenta que al final todos los elementos formarán parte de un todo.




