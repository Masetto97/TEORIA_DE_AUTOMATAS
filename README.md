# TEORIA_DE_AUTOMATAS
Se parte de un fichero de texto con información relativa a diferentes aceites esenciales, donde para cada aceite esencial se describen una serie de características de estos. Cada característica viene definida por una o varias palabras seguida de dos puntos y un texto que define a la característica.

La práctica se divide en dos módulos:

Parte 1:

Desarrollar código en Jflex que recorra el fichero de aceites esenciales, almacene en una lista los nombres de las características diferentes encontradas en el fichero y genere un fichero de texto que sea una clase en java con el siguiente contenido:

• La cabecera de la clase en java

• La definición de una variable de clase de tipo String por cada característica encontrada, de forma que las característica que se definan con más de una palabra tendrán como nombre todas las palabras unidas con un guión bajo. Por ejemplo, la característica Descripción olfativa será una variable en la clase cuyo nombre será nombre Descripcion_olfativa. También se inicializará cada variable con la cadena vacía (“”).

• Se generarán también en la clase los métodos get y put para cada variable.

Parte 2:

Desarrollar una gramática que reconozca el texto del fichero de aceites esenciales usando, como parte de los símbolo terminales, los nombres encontrados en la práctica 1 como características, usando jflex y cup para ello.

Además, se añadirán reglas semánticas a la gramática para que, a la vez que se analiza el texto se vaya generando una estructura de lista, donde cada elemento será un objeto de la clase generada en la práctica 1.
