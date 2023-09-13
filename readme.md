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

---
---
# **Ejercicio 5.1**
![Error](Ejercicio_5.1.png)

Repositorio local y remoto creados.

---
---
# **Ejercicio 5.2**
![Error](Ejercicio_5.2.png)

Creamos el readme.md dentro del directorio indicado.

---
---
# **Ejercicio 5.3**
![Error](Ejercicio_5.3.png)

Aquí he creado la rama y me he situado en ella.

---
---
# **Ejercicio 5.4**
![Error](Ejercicio_5.4.png)

Commits realizados en la rama indicada.

---
---
# **Ejercicio 5.5**
![Error](Ejercicio_5.5.png)

Antes de hacer el merge, he  realizado los push en cada rama.

---
---
# **Ejercicio 5.6**
![Error](Ejercicio_5.6.png)

Cambiamos a la rama de main e insertamos el comando 'git merge --no-f adrian12092023 -m "Ejemplo NoFF merge"'. Esto fusionará ambas ramas en la principal y todos los cambios de la rama adrian12092023 se aplicarán a la rama main.

---
---
# **Ejercicio 5.7**
![Error](Ejercicio_5.7.png)

Resultado mediante el plugin y la línea de comandos.

---
---
# **Ejercicio 5.8**
La diferencia entre FF y NoFF merges es que en FF se hace todo en una misma rama lineal hacia adelante, mientras que en NoFF, los cambios se van haciendo en ramas diferentes hasta fusionarlas en una misma.

---
---
# **Ejercicio 6**
![Error](Ejercicio_6.1.png)

Para hacer el alias, tendremos que añadirlo al archivo bashrc. Para ello, escribiremos el comando "nano ~/.bashrc" para acceder al fichero y dejaremos el fichero tal cual está en la imagen de arriba. Guardamos con Ctrl + O y salimos del fichero con Ctrl + X.

![Error](Ejercicio_6.2.png)

Al salir del archivo, escribimos "source ~/.bashrc" para recargarlo y aplicar los cambios. Ahora, cada vez que escribamos "gitadog", se nos mostrarán todos los commits; como si escribieramos "git log --all --decorate --oneline --graph".

---
---
# **Conflictos 1**
![Error](Conflictos_1.png)

Creamos un repositorio con un readme incluido.

---
---
# **Conflictos 2**
![Error](Conflictos_2.png)

Contenido copiado del repositorio.

---
---
# **Conflictos 3**
![Error](Conflictos_3.png)

Para clonar el repositorio, tendremos que copiar el enlace del repositorio remoto e insertar el comando "git clone 'enlace'", donde 'enlace' es el enlace del repositorio. Al hacerlo, se nos clonará todo el contenido en el directorio actual. Podemos comprobar también que el repositorio local está enlazado con el remoto con el comando 'git remote -v'.

---
---
# **Conflictos 4**
![Error](Conflictos_4.png)

Readme modificado en el repositorio remoto.

---
---
# **Conflictos 5**
![Error](Conflictos_5.png)

Readme modificado en el repositorio local.

---
---
# **Conflictos 6**
![Error](Conflictos_6.png)

Al intentar hacer un push en el repositorio local al remoto, nos resultará imposible debido a que hay conflictos entre ambos repositorios.

---
---
# **Conflictos 7**
![Error](Conflictos_7.png)

Introducimos 'git pull' y se nos dará a elegir la versión.

---
---
# **Conflictos 8**
![Error](Conflictos_8.png)

En mi caso, he elegido el cambio entrante, ya que me interesaba más la versión del repositorio remoto.

---
---
# **Conflictos extra**
![Error](Extra_1.png)

Por un lado, tengo mi repositorio remoto, donde todas las letras 'a' han sido cambiadas por '@'. Por otro lado, tengo mi repositorio local donde las letras 'e' han sido substituidas por '€'.

Para los reemplazos, he usado expresiones regulares.

![Error](Extra_2.png)

Esto es lo que ocurre cuando intentamos hacer un 'git pull' desde el repositorio local. Al intentar fusionar los contenidos de ambos repositorios, nos dará el resultado que se muestra en la imagen de arriba.

![Error](Extra_3.png)

He intentado combinar ambos repositorios, pero por alguna razón no me es posible.