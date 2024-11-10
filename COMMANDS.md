# COMMAND LINE 
- ¿Cómo entrar en el directorio thecmdchallenge/ ?
```bash
ls : Abre lista
```

```bash
cd thecmdchallenge/
```
- Imprimir working directory 
```bash
pwd
```
- List all the files from the current directory including the hidden ones
```bash
ls -a
```
- List all the files inside the project, recursively (all files in the hierarchy)
```bash
ls -R
```
- Clear all the command line
```bash
clear 
```
- Go to the last level below the small-name folder and show on the console the content of the trophy.txt file
```bash
ls : Abre lista
```
```bash
cd small-name/
```
```bash
find . -name "trophy.txt"
```
- Get to the funcode directory and list all files with the JavaScript typical extension
```bash
ls : Abre lista
```
```bash
cd thecmdchallenge/
```
```bash
ls
```
```bash
cd funcode/
```
```bash
ls
```
```bash 
find . -type f -name "*.js" : Para abrir los archivos con la extensión de JavaScript 
``` 
- Create a new directory inside funcode/the-most-funny/ called “not-that-funny“
```bash
cd the-most-funny/
```
```bash 
mkdir not-that-funny
```
- Create a copy of the-mostboring-text.txt (you can find it within /boringfolder/‘s children) and name it lol.txt
```bash
cd .. : x3 para ir al terminal de thecmdchallenge
```
```bash
cd thecmdchallenge/
```
```bash
ls
```
```bash
cd boringfolder/
```
```bash
ls
```
```bash
cd even-more-boring/
```
```bash
ls
```
```bash
cd i-cant-believe-how-boring/
```
```bash
ls
```
```bash
cd the-ultimate-boring-inception/ 
```
```bash
ls : Aquí encontramos e archivo .txt a copiar
```
```bash
cp the-mostboring-text.txt lol.txt : *para copiar el primer .txt y nombrarlo como el segundo .txt*
```
- Moving funcode/kids.jpg inside funcode/images/hello/
```bash
cd thecmdchallenge/
```
```bash
ls
```
```bash
cd funcode/
```
```bash
mv kids.jpg images/hello/  *mueve el archivo kids.jpg dentro de images/ dentro de hello/*
```
```bash
cd images/ 
+ 
ls 
```
```bash
cd hello
+
ls                  * Para comprobar que hemos movido bien el archivo *
```
- Removing small-name directory
```bash
cd thecmdchallenge/
```
```bash
rm -r small-name  * Borra el directorio y todo su contenido *
```
```bash
ls * Para comprobar que lo hemos eliminado *
```
- Printing in the command line the content of the-ultimate-joke.txt
1) Primero buscaría el archivo 
```bash
find -name the-ultimate-joke.txt 
= 
./funcode/the-most-funny/lol/the-ultimate-joke.txt 
(Así puedo ver la ruta que seguir)
```
2) Luego iría entrando a cada directorio que corresponde usando el comando ``` cd ```
```bash
cd lol ```dentro de este directorio se encuentra el archivo que queremos imprimir pero al ser un archivo de texto no podemos con el comando pwd```
```
3) Imprimimos el archivo
```bash
more the-ultimate-joke.txt
```
- Removing all files inside boringfolder
```bash
rm -r boringfolder
```
- Open the file kamehameha/dragon-ball-jokes.md using the VI command line text editor
1) Abrir el editor
```bash
vi kamehameha/dragon-ball-jokes.md
```
2) Para entrar en modo comando 
```bash
Esc
```
3) Ir hasta la primera línea 
```bash
gg
```
4) Selecciona la linea hasta el siguiente párrafo
```bash
v + ⬇ 
```
5) Elimina la línea seleccionada
```bash
d 
```
6) Guardar y salir 
```bash
:wq
```
