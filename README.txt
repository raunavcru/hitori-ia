La estructura de nuestro código fuente, ubicado en el fichero principal.ipynb, se resume en una celda de importaciones,
unas tres celdas en la que se definen tres clases, la clase que forma la matriz, una subclase de Acción y una última 
subclase de ProblemaEspacioEstado. Le sigue una celda en la que se definen los métodso necesarios para el calculo de
la heurística. Después, en la siguiente celda, se ha implementado un método que resuelve la matrices no un tipo de
búsquedad dado. Por último se definen la llamada a este último método y las variables asociada a esta llamada.

Para la realización de los experimentos del documento se debe introducir la matriz en la variables "estado_inicial"
y el tipo de búsqueda en un variable llamada "busqueda", que es una cadena de texto. El tipo de búsqueda del documento
es la búqeuda en profundidad, por lo que se le debe pasarle la variables con el valor 'bProfundidad'.