# Permisos de archivo

## Contenido de la Lección

Como hemos aprendido previamente, los archivos tienen diferentes permisos para los modos de archivo. Veamos un ejemplo:

<pre>$ ls -l Desktop/
drwxr-xr-x 2 pete penguins 4096 Dec 1 11:45.
</pre>

Hay cuatro partes en los permisos de fichero. La primera parte es el tipo de archivo, que se denota por el primer carácter de los permisos, en nuestro caso ya que estamos buscando en un directorio que muestra <b> d </ b> para el tipo de archivo. Más comúnmente, verá un <b>-</ b> para un archivo regular.

Las siguientes tres partes de la modalidad de archivo son los permisos reales. Los permisos se agrupan en 3 bits cada uno. Los 3 primeros bits son los permisos de usuario y permisos de grupo y luego otros permisos. He añadido el tubo para que sea más fácil de diferenciar.

<pre>d | rwx | r-x | r-x </pre>

Cada carácter representan un permiso diferente:
<ul>
<li>r: readable</li>
<li>w: writable</li>
<li>x: executable (basically an executable program)</li>
<li>-: empty</li>
</ul>

En el ejemplo anterior, vemos que el usuario Pete tiene permisos de lectura, escritura y ejecución en el archivo. El grupo penguins tiene permisos de lectura y ejecución. Y, por último, los otros usuarios (todos los demás) tienen permisos de lectura y de ejecución.

## Ejercicios

Utilice el comando ls -l en varios archivos y expone sus permisos, usuarios y grupos.

## Cuestionario de Preguntas

Qué permiso se utiliza para el ejecutable?

## Cuestionario de Respuestas

x