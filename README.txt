La estructura de nuestro código fuente, ubicado en el fichero principal.ipynb, se resume en una celda de importaciones,
otras tres celdas en la que se definen tres clases, la clase que forma la matriz, una subclase de Acción y una última 
subclase de ProblemaEspacioEstado. Le sigue una celda en la que se definen los métodos necesarios para el cálculo de
la heurística. Después, en la siguiente celda, se ha implementado un método que resuelve la matrices no un tipo de
búsquedad dado. Por último se definen la llamada a este último método y las variables asociada a esta llamada.

Para la realización de los experimentos del documento se debe introducir la matriz en la variables "estado_inicial"
y el tipo de búsqueda en un variable llamada "busqueda", que es una cadena de texto. El tipo de búsqueda del documento
es la búqueda en profundidad, por lo que se le debe pasarle la variables con el valor 'bProfundidad'.

Para leer una matriz desde un fichero txt, la matriz debe estar en una línea y seguir el siguiente patrón: número de
filas, una coma, número de columnas, una coma y la matriz. Un ejemplo: 
3,3,[[1,2,1],[2,2,1],[3,1,2]]
También podemos poner varias matrices en un mismo fichero y elegir una de ellas mediante la variable "linea" que se le pasa como parámetro
al método "leer_fichero()" junto al nombre del fichero (la primera línea será linea = 1).