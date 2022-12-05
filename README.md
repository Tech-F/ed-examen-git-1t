# 1. Creamos un proyecto con repositorio Git y código de ejemplo.
![](img/img.png)

![](img/img_1.png)

# 2. Primer commit en master.
Para realizar este paso, vamos a la carpeta del repositorio de git y abrimos git bash.
![](img/img_2.png)

![](img/img_3.png)
Como podemos observar, ya tiene el repositorio de Git creado y estamos en "Master".

Antes de realizar el primer commit, vamos a añadir los archivos que queremos de ese directorio, en este caso, todos, con el comando "git add ."

![](img/img_4.png)

Escribimos el primer commit poniendo "proyecto base" con el commando "git commit -m " " ".
![](img/img_5.png)

# 3. Creamos y resarrollamos la rama valor_referencia.
Para poder realizar esto, primero, debemos crear la rama con el comando " git branch".
![](img/img_6.png)

Una vez creada, debemos movernos a esa rama con el comando "git checkout".
![](img/img_7.png)

a)Nos vamos a Main y modificamos el codigo.
![](img/img_8.png)

b)Creamos la clase Clase y añadimos el codigo.
![](img/img_9.png)

![](img/img_10.png)

c)Añadimos nuevamente todo lo del directorio y commiteamos escribiendo "probando paso por valor y referencia".
![](img/img_11.png)

d)Modificamos nuevamente el codigo de Main y Clase, corriendolo y mejorandolo.

Main:![](img/img_12.png)

Clase:![](img/img_13.png)

e)Añadimos nuevamente todo lo del directorio y commiteamos escrbiendo "corrigido y mejorado".
![](img/img_14.png)

f)Nos vamos a GitHub y creamos un repositorio vacio.
![](img/img_15.png)

Añadimos el remote de github con el commando "git remote add origin https://github.com/Tech-F/ed-examen-git-1t.git".
![](img/img_16.png)

# 4. Hacemos un push de la rama valor_referencia.
Comando necesario "git push --set-upstream origin valor_referencia"
![](img/img_17.png)

# 5. Ahora debemos hacer un merge de esta rama a master.
Comando necesario "git merge valor_referencia master"
![](img/img_18.png)

# 6. Creamos una rama paso_arrays y la desarrollamos.
Primero hacemos un comando branch para crear y la rama y luego un checkout para entrar en ella.
![](img/img_19.png)

a) modificamos el archivo Main con el nuevo código.
![](img/img_20.png)

b) añadimos archivos del directorio y commiteamos escribiendo "pasando arrays".
![](img/img_21.png)

# 7. Hacemos un merge de la rama paso_arrays a master.
![](img/img_22.png)

# 8. Creamos las ramas comparando_objetos y comparando_strings y las desarrollamos.
a)Primero creamos comparando_objetos y la desarrollamos:
![](img/img_23.png)

a.1)Creamos una clase llamada "CompareWithEquals.java" y añadimos el código.
![](img/img_24.png)

a.2)Añadimos los archivos del directorio y commiteamos escribiendo "ejemplos de uso de equals con objetos".
![](img/img_25.png)

b)Volvemos al la rama paso_arrays con el comando "git checkout paso_arrays y creamos la nueva rama comparando_strings".
![](img/img_26.png)

b.1)Creamos la clase java "CompareWithEquals.java" y añadimos el codigo.
![](img/img_27.png)

![](img/img_28.png)

b.2)Añadimos todos los archivos del directorio y commiteamos con "probando equals con strings".
![](img/img_29.png)

b.3)Ahora hacemos merge de la rama a Master.
![](img/img_30.png)

# 9.Hacemos merge de ambas a master, solventando conflicto.

Objetos:
![](img/img_31.png)

Strings:
![](img/img_32.png)

Ahora volvemos a master
![](img/img_33.png)

modificamos el codigo de CompareWithEquals.java y commiteamos con el siguiente texto "merge de comparando_strings solventando conflicto".


**No me dio tiempo a más. Espero que esté correcto hasta aquí**

Estaba haciendo el merge al reves todo el tiempo.

Lo corrijo para poder subirlo correctamente.




