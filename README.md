
## Que es una shell

Es el programa (app) que procesa los comandos de texto y devuelva un resultado.

### Shell

Existe bash, zsh, fish

## Que es una terminal

- Normalmente se refiere a un programa que se llama simulador o emulador de terminal.
- Es un programa que te permite interactuar directamente con tu computador, a traves de procesadores de comandos como Bash.

## El poder oculto de la terminal

- Composicion de pequenas tareas

- Linux y terminales como bash fueron creados basados en otro sistema muy influyente llamado UNIX

## La filosofia de UNIX

- Escribe programas que haguen una cosa y hagan bien

- Escribe programas para trabajar juntos

- Escribe programas para manejar flujos de texto, porque esa es una interfaz universal


## Commands

Print working directory

```bash
pwd
```

Make directory

```bash
mkdir name_folder
```

Change directory

```bash
cd name_directory, cd ../
```

Clear screen

```bash
clear
```

Ingresar a la raiz del sistema operativo

```bash
cd /
```

Ingresar al home

```bash
cd ~
```

Crear archivo

```bash
touch hello.txt
```

Abrir el navegador de archivos

```bash
open .
```

Mostrar el contenido

```bash
cat hello.txt
```

Concatenar unir cadenas de texto

```bash
cat hello.txt leeme.txt
```

Mover un archivo

```bash
mv leeme.txt ./introduccion
```

Copiar un archivo

```bash
  cp leeme.txt leeme2.txt
```

Renombrar un archivo

```bash
mv leeme2.txt leeme_backup.txt
```

Copiar una carpeta recursivamente

```bash
cp -r curso_terminal/ curso_terminal_backup
```

Remove no lo envia a un trash

```bash
rm leeme_backup.txt
```

Eliminar recursivamente

```bash
rm -r introduccion
```

Crear multiples carpetas, -p (parent)

```bash
mkdir -p a/b/c
```

Listar carpetas

```bash
ls a
```

```bash
ls a/b
```

Crear multiples carpetas, -p (parent) -v (verbose) => muestra la lista de elementos que esta creando

```bash
mkdir -p -v a/b/c
```

```bash
mkdir -pv a/b/c
```

Crear multiples carpetas, para el caso de algunas distribuciones de linux puede funcionar

```bash
mkdir --parents --verbose a/b/c
```

Mostrar mas informacion acerca de un comando

```bash
man mkdir
```

Crear una carpeta con espacios

```bash
mkdir "otra carpeta"
```

```bash
mkdir 'otra carpeta 2'
```

```bash
mkdir otra\ carpeta\ 3
```

Crear multiples carpetas

```bash
mkdir "otra carpeta 4" ultima\ carpeta
```

Crear proyecto de react

```bash
npx create-react-app my_proyecto_de_prueba
```

Instalar yarn

```bash
brew install yarn
```

Instalar express-generator

```bash
npm i -g express-generator
```

Ver ayuda del comando

```bash
express --help o express -h
```

Crear un proyecto express

```bash
express --view hbs my_proyecto_de_express
```

Correr el proyecto

```bash
DEBUG=my-proyecto-express:* npm start
```

Guardar la salida de un comando en un archivo .txt

```
ls > output.txt
```

```
echo "Hola mundo terminal" > terminal.txt
```

```
cat output.txt terminal.txt
```

```
cat output.txt terminal.txt > final.txt
```

```
cat final.txt | grep terminal
```

```
cat final.txt | grep terminal > logs.txt
```
