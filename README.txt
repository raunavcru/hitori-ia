La estructura de nuestro c�digo fuente, ubicado en el fichero principal.ipynb, se resume en una celda de importaciones,
unas tres celdas en la que se definen tres clases, la clase que forma la matriz, una subclase de Acci�n y una �ltima 
subclase de ProblemaEspacioEstado. Le sigue una celda en la que se definen los m�todso necesarios para el calculo de
la heur�stica. Despu�s, en la siguiente celda, se ha implementado un m�todo que resuelve la matrices no un tipo de
b�squedad dado. Por �ltimo se definen la llamada a este �ltimo m�todo y las variables asociada a esta llamada.

Para la realizaci�n de los experimentos del documento se debe introducir la matriz en la variables "estado_inicial"
y el tipo de b�squeda en un variable llamada "busqueda", que es una cadena de texto. El tipo de b�squeda del documento
es la b�qeuda en profundidad, por lo que se le debe pasarle la variables con el valor 'bProfundidad'.