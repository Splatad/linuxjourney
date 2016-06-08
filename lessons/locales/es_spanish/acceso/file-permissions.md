# Permisos de archivo

## Contenido de la Lección

Como hemos aprendido previamente, los archivos tienen diferentes permisos para los modos de archivo. Veamos un ejemplo:

<pre>$ ls -l Desktop/
drwxr-xr-x 2 pete penguins 4096 Dec 1 11:45.
</pre>

Hay cuatro partes en los permisos de fichero. La primera parte es el tipo de archivo, que se denota por el primer carácter de los permisos, en nuestro caso ya que estamos buscando en un directorio que muestra <b> d </ b> para el tipo de archivo. Más comúnmente, verá un <b>-</ b> para un archivo regular.

Las siguientes tres partes de la modalidad de archivo son los permisos reales. Los permisos se agrupan en 3 bits cada uno. Los 3 primeros bits son los permisos de usuario y permisos de grupo y luego otros permisos. He añadido el tubo para que sea más fácil de diferenciar.