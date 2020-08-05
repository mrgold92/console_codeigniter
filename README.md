# CONSOLE CODEIGNITER



[TOC]

Pequeño script en bash para poder crear la base básica de un controlador o un modelo en codeigniter.

## USO

Deberemos poner el archivo `console` dentro del directorio **raíz** de nuestro proyecto.

```
📦project
 ┣ 📂public
 ┣ 📂tests
 ┣ 📂vendor
 ┣ ...
 ┗ 📜console

```
> Es muy importante que el archivo **console** esté dentro de la carpeta raíz de nuestro proyeco de codeigniter.

## Para usarlo:

Desde la consola de comando y estando posicionados en la raíz del proyecto, pondremos:

```bash
usuario@NOMBRE MINGW64 /ruta/raiz 
$ . console <args> 

```

### Argumentos:

####  Crear un nuevo controlador:

```bash
$ . console -m controller Users
```

#### Crear un nuevo modelo:

```bash
$ . console -m model Posts
```

### Ayuda:

make | -m controller|model < name >  Create a controller or a model.

help | - h muestra la ayuda.



## ENGLISH VERSION

Small bash script to create the basic foundation of a controller or a model in codeigniter.

## USE

We will have to put the console file inside the **root** directory of our project.

```
📦project
 ┣ 📂public
 ┣ 📂tests
 ┣ 📂vendor
 ┣ ...
 ┗ 📜console

```

> It is very important that the **console** file is inside the root folder of our codeigniter project.

## To use it:

From the command console and being positioned at the root of the project, we will put

```bash
usuario@NOMBRE MINGW64 /ruta/raiz 
$ . console <args> 

```

### Arguments:

####  Create a new controller:

```bash
$ . console -m controller Users
```

#### Create a new model:

```bash
$ . console -m model Posts
```

### It helps:

make | -m controller|model < name >  Create a controller or a model.

help | - h shows the help.