CONCEPTOS APRENDIDOS

En este módulo aprendí a:

1. Configurar ambiente de trabajo

en esta sección, vimos cómo instalar las siguientes herramientas:

* Visual Studio Code => Es el IDE de desarrollo, donde escribiremos el código de nuestro proyecto.
Ingresamos a la página principal de la misma, descargamos el IDE e instalamos la aplicación (Siguiente, 
Siguiente).
* Git => Es un sistema de control de versiones del proyecto. Permite gestionar los cambios del proyecto, 
guardando sus diferentes versiones.
* GitHub => ES una plataforma donde subimos los proyectos, podemos compartir archivos con personas y quién hace 
qué, sobre el proyecto.
* Wakatime => Es una herramienta que nos permite ver el tiempo que invertimos en la implementación de nuestros 
proyectos, así como también permite 
ver los lenguajes utilizados, con sus respectivos porcentajes.

- Descargamos Visual Studio Code.
- Descargamos GitBash y lo configuramos, con los siguientes comandos:

git config --global user.name "Angela Guarin"  =>Nombre con el cual nos identificaremos.
git config --global user.emal "gurive.3@gmail.com" => E-mail que vamos a utilizar, al momento de crear la cuenta 
en GitHub.

- Verificamos la configuración de GitBash, así:

git config --list  => nos muestra el nombre y el correo que ingresamos anteriormente.

- Creamos una cuenta en GitHub. (Utilizamos el E-mail, que ingresamos en la configuración de GitBash)
- Instalamos Wakatime. Esta herramienta está como extensión en Visual Studio Code, por lo que la instalamos como 
tal, así:
En la opción "Extensiones", buscamos "Wakatime", la instalamos. Una vez instalada, cerramos y volvimos a abrir 
Visual Studio Code.
Después, presionamos F1, y en la barra de búsqueda, ingresamos "wakatime". Vemos que nos solicita una "key". 
Esta key, la obtenemos
de la página oficial de wakatime; por lo cual nos registramos allí con la cuenta de GitHub que creamos. Una vez 
registrados,
copiamos la "key" y en Visual Studio Code, la pegamos. 
En la parte inferior izquierda, observamos un relojito de sincronización, lo que indica que Wakatime, ya está 
configurado en VS Code.

2. Comando de Linux

* pwd => Para saber dónde estamos ubicados.
* ls => Para listar los archivos que contiene una carpeta.
* Clear => Para limpiar pantalla.
* mkdir => Para crear un directorio.
* touch => Para crear un archivo.
* nano => Para crear un archivo con editor abierto listo para escribir información.
* cd .. => Para subir un nivel de la carpeta.
* rs -rf Git/ => rs -rf <nombre carpeta> para borrar una carpeta. 

3. Comandos Git

* git init => Para inicializar el repositorio.
* git status => Para ver el estado de los archivos del repositorio local. (Rojo, indica que aún no se han 
subido. Verde, indica que ya se agregaron.)
* git add . => Agrega los archivos a GitHub. Para agregar un archivo en específico: git add nombre_archivo
* git commit -m "prueba mensaje" => Para vincular el repositorio local con la plataforma.
* git remote add origin url_repositorio => Para indicar el repositorio donde lo va a guardar.
* git push origin master => Para entregar los archivos.
* git pull origin master => Para bajar archivos de GitHub al Git local.

4. Git Pages

Se realizó una configuración para publicar el proyecto en GitHub. (El paso a paso , se mostrará en imágenes más 
adelante)

5. MarkDown

Es un lenguaje de marcado de hipertexto, parecido a HTML.

# => tamaño parecido a h1
## => tamaño parecido a h2
### => tamaño parecido a h3

Listas ordenadas:

- Casa
- Perro
- Carro

1. Casa
2. Perro
3. Carro

Bloques de información:

~~~
Hola a todos!
~~~

Agregar una imagen:
![Casa] (url_imagen_casa)

Hipervínculo:
[Google] (url_google)

Listas de tareas:
- [x] Tarea

Separar bloques de código:
```
html<h2>Hola a todos!</h2>
```


