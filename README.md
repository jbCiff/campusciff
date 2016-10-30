# Parte 1 #

### Clonar:

~~~
git clone git@github.com:jbCiff/campusciff.git
~~~


### Escribir en .gitignore: 

+ privada
+ privada.txt




### añadir tag a fichero 1.txt

~~~
git tag v0.1
~~~

### subir cambios del fichero 1.txt
~~~
git add 1.txt
git commit -m "etiqueta v0.1"
git push origin master
~~~

### Subir arhivo README.md
~~~
git add README.md
git commit -m "commit inicial 2"
git push origin master
~~~



### Listado

| Nombre   | GITHUB                                   |
| ------   | -----:                                   |
|  ediboc  |   git@github.com:jbCiff/CampusCiff-1.git |
|  carlosmunvaz|   https://github.com/carlosmunvaz/campusciff.git                                      |
|  vacio   |   -                                      |



--------------------------

# Parte 2 #


### Rama v2.0

Crear rama y fichero 2.0.txt
~~~
git branch v2.0
git checkout v2.0
git add 2.txt
git commit -m "rama 2.0"
~~~


posicionarse en el master
~~~
git checkout master
~~~


unir las ramas
~~~
git checkout v0.2
~~~


unir las ramas con conflictos
~~~
git checkout v0.2
~~~

Aqui solucionar los conflictos manualmente (notepad), después
~~~
git add 1.txt
git commit -m "merged master"
~~~

Imagen de las ramas unidas

![picture alt](/ramas_unidas.png) 







