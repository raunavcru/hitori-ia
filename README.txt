La estructura de nuestro c�digo fuente, ubicado en el fichero principal.ipynb, se resume en una celda de importaciones,
otras tres celdas en la que se definen tres clases, la clase que forma la matriz, una subclase de Acci�n y una �ltima 
subclase de ProblemaEspacioEstado. Le sigue una celda en la que se definen los m�todos necesarios para el c�lculo de
la heur�stica. Despu�s, en la siguiente celda, se ha implementado un m�todo que resuelve la matrices no un tipo de
b�squedad dado. Por �ltimo se definen la llamada a este �ltimo m�todo y las variables asociada a esta llamada.

Para la realizaci�n de los experimentos del documento se debe introducir la matriz en la variables "estado_inicial"
y el tipo de b�squeda en un variable llamada "busqueda", que es una cadena de texto. El tipo de b�squeda del documento
es la b�queda en profundidad, por lo que se le debe pasarle la variables con el valor 'bProfundidad'.

Para leer una matriz desde un fichero txt, la matriz debe estar en una l�nea y seguir el siguiente patr�n: n�mero de
filas, una coma, n�mero de columnas, una coma y la matriz. Un ejemplo: 
3,3,[[1,2,1],[2,2,1],[3,1,2]]
Tambi�n podemos poner varias matrices en un mismo fichero y elegir una de ellas mediante la variable "linea" que se le pasa como par�metro
al m�todo "leer_fichero()" junto al nombre del fichero (la primera l�nea ser� linea = 1).