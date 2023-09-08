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