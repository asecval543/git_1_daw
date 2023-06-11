# git_1_daw
Este repositorio  consiste en la tarea de la unidad 3 

## Comando que he  utilizado para clonar el repositorio
git clone git@github.com:asecval543/git_1_daw.git [Clonara dicho repositorio]<br>

## Comando que he utilizado para el commit inicial y push inicial
git add README.md [Va ha añadir dicho archivo]<br>
git commit -m ”commit Inicial” [Va ha hacer un commit inicial]<br>
git push [Sube cambios en el repositorio]<br>

## Comando que he utilizado para ignorar archivos
touch privado.txt [Crea dicho fichero]<br>
mkdir privada [Crea la carpeta privada]<br>
nano .gitignore [Se3 edita el archivo .gitignore]<br>
git add .gitignore [Añadir archivo .gitignore]<br>
git commit -m “he añadido  .gitignore” [hace commit y dicho mensaje  de que se ha añadido el.gitignore]<br>
git push [Sube los cambios a dicho repositorio]

## Comando que he  utilizado para Añadir fichero 1.txt y Añadir tag v.0.1
touch 1.txt [Crea el fichero 1.txt]<br>
git add 1.txt [Añade el fichero 1.txt]<br>
git tag v.0.1 [Crea el tag llamadov.0.1]<br>
git commit -am ”añadido 1.txt y el tag v.01” [Haze commit con dicho mensaje]<br>
git push [Sube los cambios del repositorio]

## Tabla de compañeros

| NOMBRE | GITHUB|
|--------|------|                   	 
| Pablo  | [github 1](https://github.com/pamadob/) |  
| Antonio| [github 2](https://github.com/anuncar621508)  |
| Jose D | [github 3](https://github.com/jjunlob074)   |

##  Comando que he  utilizado para Crear una rama, Crear la rama v0.2 
## Posiciona tu carpeta de trabajo en esta rama. Añadir fichero 
##  Añadir un fichero 2.txt en la rama v0.2

git branch v.0.2 [Crea una nueva rama]<br>
git checkout v.0.2 [Para cambiar al branch (rama]<br>
touch 2.txt [Crea el fichero 2.txt]<br>
git add 2.txt [Añado el archivo 2.txt]<br>
git commit -m “añadido el archivo 2.txt  a la rama v.0.2” [Se hace el commit con dicho mensaje]<br>
git push -u origin v.0.2 [ Envía los cambios realizados en la rama "v0.2"]
 
## Comando que he utilizado para  Borrar rama ,Crear un tag v0.2 y Borrar la rama v0.2
git tag v.0.2 [para crear una etiqueta  llamada v.0.]<br>
git checkout v.0.2 [ sirve para cambiar a una versión específica de un repositorio.]<br>
git checkout main[para cambiar a la rama principal]<br>
git branch -D v.0.2  [eliminar de forma forzada una rama con el nombre "v0.2"]<br> 
git log –graph [mostrar el historial de commits.]
