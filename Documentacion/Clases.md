16 de noviembre del 2022 </h1>
##### Maximiliano Madrid Benavides
# <h1 style="color: #7FFF00"> CLASE 3 - Git + Markdown

Despues de haber creado nuestra carpetta Gitmarkdown en nuestro repositorio y agregarlo a nueestro editor Visual Studio Code


Aprendimos los siguientes comandos en Markdown

___
##### <div style="background-color:#FFFF00"> <h1 style ="color: #000000">***Tamaño de títulos*** </div>

- Titulo  1:  #

- Titulo  2:  ##

- Titulo  3:  ###

- Titulo  4: ####

- Titulo  5: #####

### ***Diseño de texto***

Negritas command: ** la palabra 

Cursiva command: * koa *

Negritas con cursiva command: *** Pac.mi ***

Tachado command: ~~ Tachado ~~

### ***Marco obscuro***

Tras 4 espaciados dispondemos nuestro texto en Un marco obscuro.

    Como se muestra a continuacion:_____"Lo que se deasea escribir", siendo(_) notacion de espaciado.
### ***Marco con diseño de lenguajes de programación a gusto*** 
Tras escribir 4 apostrofes, procedemos a escribir nuestro lenguaje deseado.

````cpp

int main(){

printf("Hola mundo")


    return 0;
}
````
> ## Cosas adicionales durante la clase

- pwd => En que directorio estoy
- ls => En que carpeta me encuentro
- git init => Empezar el seguimiento de git
- git add . => Agregar todos nuestros archivos 
- git status => Estado de nuestro seguimiento
- git add index.html => Agregar archivo personalizado
- echo tmp.txt >> .gitignore => Ignorar un archivo
- git status
- echo .gitignore >> .gitignore => Ignorarse así mismo
- cat index.html => Que se encuentra dentro de mi archivo
---
[ ] Codigo dentro de .gitignore para dejar de seguir archivos con terminacion general.

1.*.txt

---
>***Creamos nuestro primer tag o etiqueta de trabajo***



Esto quiere decir tener hasta cierto punto en el tiempo, Todo nuestro trabajo ya registrado dentro de nuestro git 

## Con el comando: 
- git -m "nombre de la version" 

---

##### 18 de noviembre del 2022
##### Maximiliano Madrid Benavides
# <h1 style="color:#8B0000">CLASE 4 - Intro To C

Empezamos en nuestra clase con una explicacion general de git revisando comandos vistos previamente y reforzando sus aplicaciones.

><h1 style="color: orange">Los mas usuales como:

```
=> git version
=> gcc --version
=> pwd
=> ls
=> git add .
=> git status
=> echo .gitignore >> .gitignore
=> git commit -m"Version1"
=> clear 
=> History 
````

### Llevamos a cabalidad nuestro primer hola mundo en el lenguaje de C

````c
int main(){

printf("Hola mundo")


    return 0;
}
````
***Primero nos aseguramos de que nuestro codigo funcionace:***

1. Primero Nuestro codigo para ejecutar el compilador

`g++ src/main.c -o output/main.exe`

![Hola](https://ibb.co/WnSWgYn)

###### <div style="background-color:#F5F5DC"><h1 style="color: #0000CD"> LLevamos nuestros tags/ commits a la nube:

