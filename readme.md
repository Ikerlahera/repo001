# Crear repositiorio en git

![alt text](image-6.png)

1. Añado el usuario

![alt text](image-7.png)

2. Y el email 
   
![alt text](image.png)

3. Utilizando el comando git init "nombre del repositorio", creamos una carpeta que contiene un repositorio de git en su interior.

![alt text](image-1.png)

4. Añado el fichero al stagin area con el comando add.

![alt text](image-2.png)

5. Compruebo el estado.

![alt text](image-3.png) 

6. Y ahora hago un commit al repositorio local. El fichero ahora esta en estado "Commited"


![alt text](image-4.png)

7. Si hacemos un push da un error, si hacemos un git remote -v veremos que no aparece nada, esto se debe a que no tenemos el repositorio local asociado a ningun repositorio remoto.  Para añadir el repositorio local al repositorio remoto utilizo el comando "git remote add origin" y el enlace al repositorio remoto.

![alt text](image-5.png)

8. Para hacer el primer push lo pongo con -u origin master o --set-upstream origin master. Para los proximos push bastara con poner simplemente un git push
