## ¿Utilidad?
> Esta herramienta es una herramienta que sirve para acceder a tus apuntes de forma más rapida , de manera que si tienes apuntes en un archivo en concreto con este programa te puede represetnar la informácion de el apartado que necesitas simplemente poniendo su nombre.

## ¿Cómo funciona?
> Pues esta herramienta esta escrita en "BASH" y funciona de la siguiente manera. La herramienta necesita de un archivo de apoyo para funcionar (archivo donde se encuentran todos tus apuntes) , lo que va a hacer la herramietna es buscar una sentencia que tienes que poner cada vez que deseas acceder a un apunte de manera que la herramietna buscara el texto que se encuentra entre esa sentencia y te lo reportara por pantalla

> En esta herramienta he añadido algo de apuntes aleatorios para que veais como funciona , pero esto lo podeis implementar con todos los vuestros

![[Pasted image 20230222161352.png]]

1. **all_data.txt** : Archivo donde se encuntran los apuntes
2. **consolecheat.sh** : Archivo ejecutable

## En ejecución
![[Pasted image 20230222161523.png]]

> Vamos a hacer la prueba de buscar los apuntes que hablen sobre los PERMISOS

![[Pasted image 20230222161610.png]]


## Explicación de el código
![[Pasted image 20230222162048.png]]

![[Pasted image 20230222161855.png]]

> Este es el archivo "all_data.txt" , como vemos lo que hemos buscado anterirormente se encuentra entre dos "Sentencias" (:S.PERMISOS) , lo que hace el script es buscar todo lo que este entre esa sentencia y reportarlo por pantalla

> El core de la herramienta se basa en la siguente función:

![[Pasted image 20230222161715.png]]

# Versión
> Actualmente esta en la versión v1.0

# Autor
> Tuch0: https://github.com/Tuch0
> WEB: https://tuch0.github.io

