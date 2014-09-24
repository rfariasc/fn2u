
# fn2u: Filename to Unix  


Sintaxis: fn2u [directorio] [n]

n=1 Sólo lista los archivos o directorios con sus rutas completas que poseen alguno de los siguientes caracteres: espacio, letras acentuadas (á, é, í, ó, ú), ñ, Ñ.
n=2 Renombra archivos y  directorios que contengan alguna de las letras indicadas previamente. Los espacios deben ser reemplazados por "_", las vocales acentuadas se cambian por la misma vocal no acentuada, ñ cambia a n y Ñ a N.


Descripción
  En la ausencia de el primer argumento se procede la búsqueda en el directorio actual. La ausencia del segundo argumento toma n=1. Si hay sólo un argumento, éste debe ser el directorio al cual se desea hacer el análisis. 
  fn2u con opción n=1 permite listar por la salida estándar la ruta completa y los nombres de archivos y directorios que incluyen alguno de los siguientes caracteres: espacios, letras acentuadasa (á, é, í, ó, ú), ñ, Ñ. La opción n=2 permite renombrar los archivos generando un cambio en el directorio. Si el mismo nombre ya existe, el nuevo nombre es extendido agregando _1, si por alguna razón, este ya existe, continúa con _2 y así.

