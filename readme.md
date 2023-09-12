# **Ejercicio 1.1**
![Error](Ejercicio_1.1.png)

Para transformar el directorio en un repositorio local, nos situaremos en el directorio desde la terminal y escribiremos el comando 'git init'. Este comando permitirá iniciar el repositorio.

En la imagen se pueden apreciar dos círculos rojos que indican que el repositorio local se ha creado exitosamente:
- Se crea un archivo llamado ".git" en el directorio.
- En la terminal hay un "(master)" al lado de la dirección del directorio.

---
---
# **Ejercicio 1.2**
![Error](Ejercicio_1.2.png)

La documentación de los ejercicios se hará en un archivo de formato Markdown.

---
---
# **Ejercicio 1.3**
![Error](Ejercicio_1.3.1.png)

Al crear un archivo en el repositorio, primero tenemos que mover los archivos al staging area. Si no lo hacemos, los archivos saldrán marcados como Untracked.


![Error](Ejercicio_1.3.2.png)

Para solucionar esto, escribimos por terminal el comando 'git add .', donde se añadirán todos los archivos del directorio al staging area. Si volvemos a comprobar el estado, los archivos saldrán en verde.


![Error](Ejercicio_1.3.3.png)

Finalmente, para pasarlos al repositorio pondremos el comando 'git commit -m "mensaje"', donde "mensaje" es el comentario que pondremos para el commit. A este punto, el fichero se encuentra en el estado 'commited' del 'file status lifecycle'.

---
---
# **Ejercicio 1.4**
![Error](Ejercicio_1.4.png)

Al escribir el comando 'git push', nos saldrá un error y aparentemente no ocurrirá nada. El problema es que no hemos creado un repositorio en GitHub y tampoco hemos asociado la dirección del mismo.

---
---
# **Ejercicio 1.5**
![Error](Ejercicio_1.5.png)

Al escribir el comando 'git remote -v', no nos aparecerá nada. Esto es normal, ya que no tenemos ningún repositorio remoto asociado.

---
---
# **Ejercicio 1.6**
![Error](Ejercicio_1.6.1.png)

Una vez creado el repositorio, estos serán los comandos que tendremos que utilizar para asociar el repositorio.

![Error](Ejercicio_1.6.2.png)

---
---
# **Ejercicio 1.7**
![Error](Ejercicio_1.7.png)

Al escribir de nuevo el comando 'git remote -v', nos saldrá el repositorio remoto asociado. Ahora sí que aparece debido a los comandos que hemos introducido anteriormente.

---
---
# **Ejercicio 1.8**
![Error](Ejercicio_1.8.png)

Aquí he subido todos los cambios que llevamos hasta ahora.

---
---
# **Ejercicio 1.9**
![Error](Ejercicio_1.9.png)

Los cambios se han realizado correctamente desde el repositorio local. La documentación Markdown se mostrará debajo de los archivos subidos.

---
---
# **Ejercicio 2.1**
![Error](Ejercicio_2.1.png)

Repositorio 'repo02' creado. En este caso, se le considera un repositorio remoto debido a que solo se encuentra en GitHub y no tiene un directorio local asociado.

---
---
# **Ejercicio 2.2**
![Error](Ejercicio_2.2.png)

Copiamos la dirección del repositorio remoto de repo01, accedemos a un directorio distinto y escribimos el comando 'git clone "dirección"', donde "dirección" es la dirección del repositorio remoto. Al hacerlo, se nos clonará el repositorio.

---
---
# **Ejercicio 2.3**
![Error](Ejercicio_2.3.png)

Commit realizado en el repositorio clonado.

---
---
# **Ejercicio 2.4: Resumen**
| Comando | Función |
|:--- |:--- |
| git config | Permite configurar el nombre y correo del usuario
| git init | Inicializa el repositorio |
git status | Permite ver el estado de los ficheros |
| git add | Añade los ficheros al staging area |
| git commit | Envía los ficheros añadidos al repositorio local |
| git log | Muestra un historial de los commits |
| git remote add origin | Enlaza el repositorio local con el remoto |
| git branch | Cambia el nombre de la rama |
| git remote -v | Muestra los repositorios remotos asociados |
| git push | Sube los cambios a un repositorio remoto |
| git clone | Clona un repositorio |

---
---
# **Ejercicio 4.1**
![Error](Ejercicio_4.1.png)

Repositorio creado en local y en remoto.

---
---
# **Ejercicio 4.2**
![Error](Ejercicio_4.2.png)

Añadido el fichero readme.md al repositorio remoto.

---
---
# **Ejercicio 4.3**
![Error](Ejercicio_4.3.png)

Para crear una rama, usaremos el comando "git branch fastforward". Esto creará la rama 'fastforward'.

Para pasar a esta rama, insertamos en la terminal "git checkout fastforward". Al escribir este comando, nos localizaremos en la rama 'fastforward'.

---
---
# **Ejercicio 4.4**
![Error](Ejercicio_4.4.png)

Fichero readme.md editado.

---
---
# **Ejercicio 4.5**
![Error](Ejercicio_4.5.png)

Aquí se muestran todos los commits que se han hecho. Como se puede ver, se han hecho 3 commits desde la rama 'fastforward'.

---
---
# **Ejercicio 4.6**
![Error](Ejercicio_4.6.1.png)

Ahora vamos a fusionar las ramas y realizar los cambios hechos por la rama 'fastforward'. Para hacerlo, cambiaremos a la rama 'main' e introduciremos el comando "git merge fastforward".

![Error](Ejercicio_4.6.2.png)

A continuación, hacemos un push y los cambios del commit se nos actualizarán en el repositorio remoto.

---
---
# **Ejercicio 4.7**
![Error](Ejercicio_4.7.png)

Eliminamos la rama anteriormente creada con el comando "git branch -d fastforward".

---
---
# **Ejercicio 4.8**
![Error](Ejercicio_4.8.png)

Como se puede comprobar, el comando para eliminar la rama ha funcionado correctamente.