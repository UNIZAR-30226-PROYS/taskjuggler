# Práctica de Proyecto Software - "Planificación"

Este repositorio usa GitHub Actions para ejecutar [TaskJuggler](https://taskjuggler.org) tomando como entrada el fichero de definición de proyecto P5_proySW.tjp y generando un conjunto de informes que se pueden descargar desde la pestaña de Actions.

## Instrucciones

Tienes que hacerte un fork del repositorio, clonarlo en tu equipo, y ahí hacer las modificaciones que quieras al fichero P5_proySW.tjp para cumplir lo que se pide en la práctica. 

Cuando quieras generar los resultados, tienes que hacer commit de los cambios realizados en P5_proySW.tjp, hacer push al repositorio del que has hecho fork (todo por defecto, a la rama main), ir a la pestaña de GitHub Actions, comprobar si se ha ejecutado sin errores y, si es así, te aparecerá abajo, en la sección de Artefactos, un enlace a un fichero results.zip, que puedes descargar, con el resultado de haber ejecutado el comando `tj3 -o results P5_proySW.tjp`.

Si tu fichero tiene errores de sintaxis, podrás examinar los resultados de la ejecución (fallida) de GitHub Actions para comprobar qué mensajes de error se han generado y depurarlo usando esa información.
