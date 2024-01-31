# Practica_evaluable

Este es un pequeño tutorial hecho para una práctica de clase de como empezar a trabajar con Git desde cero con comandos muy sencillos y algunos más avanzados. Tambien algunos tips y cosas a saber para principiantes.

Código utilizado:

- Git --version: comprobar la versión de tu S.O.

- Git config --global user.name “Marcos Rodriguez”: establecer nombre de usuario.

- Git config --global user.email peliculasypublicidad@gmail.com: email con el que trabajaremos.

- Git config --global core.editor “code --wait”: configurar el Visual Code como nuestro editor y esperar a que se cierre para poder continuar por la terminal.

- Git config --global -e: mirar nuestro archivo de configuración global dentro VSCode.

- Cd ../Entornos de desarrollo: dirigirnos al directorio donde realizaremos el trabajo.

- Mkdir Practica_Evaluable: creamos la carpeta.

- Ls: comprobar que estamos en la carpeta que queremos.

- Code .: Abrirá en VSCode la carpeta donde nos encontramos.

- Git status: Mostrará el estado actual de nuestros repositorios y los archivos que Git está o no siguiendo (por defecto no los seguirá hasta seleccionarlos).

- Git add *txt: seleccionará todos los archivos con una extensión .txt. Como en este caso los dos tienen esa extensión lo haremos así, si no pondremos directamente el nombre de nuestros archivos separados con un espacio y su extensión.

- Git status: para comprobar otra vez que nuestros dos archivos están en el área de trabajo.

- Git add *.txt: para validarlos de nuevo.

- Git commit -m “Commit”: cambios commiteados.

- Git add documento2.txt: Volvemos a añadirlo al área de trabajo.

- Git commit: Abrirá directamente VSCode y escribiremos el mensaje que se mostrará por la terminal, que nosotros queramos indicar para estos cambios (en mi caso, “Asignatura añadida”.

- Echo “Holi Mundi\nHoli Mundi2\nHoli Mundi3” > documento1.txt: se crea y se añaden líneas por pantalla a nuestro documento1.txt.

- Git add documento1.txt: se añade.

- Echo “Asignatura: entornos de desarrollo” >> documento2.txt:

- Git reset --hard HEAD^: Volver al estado anterior documento2.txt.

- Git log --oneline: mostramos commit realizados hasta el momento y estado de documento1.txt (el doc2 está en la captura anterior).

- Git revert HEAD: revertimos el último commit donde validamos el doc3.


- Git remote add origin https://…git: vinculamos cuentro nuestro repositorio remoto.

- Git push -u origin master: lanzamos nuestro repositorio a git hub.

- Git checkout mirama: cambiamos al directorio mirama.

- Git checkout master (main): cambiamos el directorio de trabajo a la versión de mirama (aquí también podemos usar git switch mirama para cambiar entre ramas. O git switch -c mirama para crear una rama y cambiar a ella).

- Git merge mirama:  fusionamos la rama mirama con la rama master o main.

- Git branch -d mirama: eliminamos la rama del repositorio.

- Git push origin master: sincronizamos con nuestro repositorio remoto.

- Git tag V1: creamos la etiqueta V1.

- Git push –tags: la lanzamos al repositorio remoto.

- Git clone https://github.com/Ravachol88/practica_evaluable practica_evaluable_2: hacer un clonado del repositorio remoto a un nuevo directorio.

- Git switch master/main: cambiar a rama master.

- Code .: ir a VSCode.

- Echo “# Practica_Evaluable” > README.md: creamos el Readme.

- Git pull origin master: llevar cambios del repositorio remoto al local.