Melanie Pérez
melanie.perez@alumnos.uv.cl

echo : se utiliza para dar el mensaje de que el archivo fue creado con éxito.

curl : Se útilizó para transferir los datos de la URL entregada.

-s : se utilzó para que al correr el programa no se visualicen datos inncesarios en la consola y sólo se visualice lo que se está pidiendo.


jq 'del()' : se utilizó para filtrar y eliminar los datos que no innecesarios según indican las instrucciones.

> : se utiliza para redireccionar la información y guardarla en un archivo. 

| : se utiliza para dar más de una instrucción a realizar.

Explicación del diseño solución:

Al plantear el problema y comenzar la búsqueda de la solución lo primero fue revisar los links entregados en el documento para encontrar información sobre los comandos que se indican. Luego probar los comandos por separados para ver su correcta ejecución y luego buscar la forma que fuera más sencilla para eliminar los datos que no se pedían.
Por lo que el resultado final es una línea de comando que transfiere los datos desde la URL entregada, luego se filtran los datos que no se van a utilizar (ambos comandos unidos por un pipe) y finalmente utilizando redireccionamiento de datos se guarda la información que se pide en un archivo de nombre items.json. Una vez lista la línea de comando se crea un archivo con el nombre indicado y dentro se guarda la línea echo JSON CREADO CON EXITO, más la línea de comando recién creada. De esta forma cuando se llame el archivo se creará el archivo.json que contiene los datos requeridos y mostrará el mensaje de que fue creado con éxito.

links utilizados:
https://www.krenger.ch/blog/jq-delete-an-element-from-an-array/
# SSOO-tarea02
 
