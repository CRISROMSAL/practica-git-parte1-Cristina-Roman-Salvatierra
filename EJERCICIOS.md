PARA VER UNA DOCUMENTACIÓN MAS COMPLETA CON CAPTURAS DE PANTALLA, EN CLASSROOM HE SUBIDO UN ARCHIVO PDF MUCHO MAS COMPLETO.

hemos creado el archivo notas y lo abrimos con visual para añadir asignaturas
Hacemos commit y push para guardarlo y subirlo.
Hemos abierto el archivo de notas y hemos añadido nuevas asignaturas
Hemos hecho un commit directo com -am y un push
Hemos creado la rama feature-tareas y hemos editado el archivo notas y hemos añadido una lista de tareas pendientes
Hemos hecho commit y lo hemos subido con git push -u origin feature tareas
Volvemos al main y fusionamos con merge y lo subimos
Borramos la rama en el local
Borramos la rama en GitHub
Vamos a crear un archivo temporal.txt y vamos a añadir contenido
Lo añadimos al repositorio con add y commit
Borramos el archivo temporal
Ahora vamos a probar a restaurarlo (tal y como se indica en los apuntes con el restore nos da problemas, no nol restauraba el archivo, así que hemos buscado otra forma de hacerlo.)
Hacer dos commits modificando el mismo archivo, notas.md. Vamos a añadir notas de las asignaturas dos veces.
Usa git log –oneline –graph –all.
* (asterisco) → Marca cada commit
Código corto (abc1234) → Hash único del commit (identificador)
Mensaje → La descripción que escribiste en el commit
--oneline → Muestra cada commit en una sola línea (más legible)
--graph → Muestra visualmente las ramas y fusiones
--all → Muestra todos los commits de todas las ramas
Usa git diff HEAD~1 HEAD 
HEAD~1 → El commit anterior
HEAD → El commit actual (más reciente)
Líneas con + → Contenido que se añadió (en verde)
Líneas con - → Contenido que se eliminó (en rojo)
diff --git → Qué archivo cambió
Te muestra exactamente qué líneas cambiaron entre esos dos commits
Creamos la rama feature conflicto y cambiamos a esta rama
Abrimos Visual Studio Code y modificamos una línea específica, en mi caso voy a modificar las notas de diseño de interfaces web y desarrollo web en entorno servidor, líneas 21 y 22 
hacemos commit y lo subimos a GitHub
Ahora cambiamos a la rama main, abrimos code y vamos a volver a modificar las notas de esas dos líneas
Ahora hacemos el commit y lo subimos a GitHub
Ahora fusionamos y tenemos que resolver el conflicto
Ahora marcamos el conflicto como resuelto y subimos los cambios a GitHub
Ahora creamos el archivo conflicto.md para documentar cómo resolvimos esto
Hacemos commit y subimos a GitHub
Crear un tag ligero y subirlo a GitHub
Crear un tag anotado con mensaje
