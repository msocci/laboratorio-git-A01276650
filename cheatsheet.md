# Git Cheatsheet

## git status
Sirve para revisar el estado actual del repositorio. Te muestra qué archivos modificaste, cuáles ya están preparados para un commit y cuáles todavía no.

## git add
Sirve para preparar los cambios que quieres incluir en el siguiente commit. Por ejemplo, git add . agrega todos los cambios que hayas hecho.

## git commit
Guarda los cambios que preparaste con git add como una nueva versión del proyecto. Normalmente se agrega un mensaje para explicar qué hiciste.

Ejemplo: git commit -m "Agregué cambios al proyecto"

## git push
Sube los commits que tienes en tu computadora al repositorio remoto, por ejemplo en GitHub. Así los cambios quedan disponibles para los demás integrantes del equipo.

## git pull
Descarga los cambios más recientes del repositorio remoto y los integra en tu proyecto local. Es útil para tener la versión más actualizada del trabajo.

## git log
Muestra el historial de commits del proyecto. Sirve para revisar qué cambios se han guardado anteriormente, quién los hizo y cuándo.

## git diff
Muestra exactamente qué cambió en los archivos. Te permite revisar las líneas que agregaste, eliminaste o modificaste antes de guardar los cambios.

## git restore
Sirve para deshacer cambios que hiciste en un archivo y regresar a la última versión guardada.

Ejemplo: git restore archivo.ipynb

## git restore --staged
Sirve para quitar un archivo del área de preparación después de haber usado git add, pero sin borrar los cambios que hiciste en el archivo. Es útil cuando agregaste algo por error y todavía no quieres incluirlo en el próximo commit.

Ejemplo: git restore --staged archivo.ipynb