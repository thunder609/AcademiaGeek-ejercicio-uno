# Ejercicios Módulo 0
Despues de haber descargado todos mi entorno de desarrollo procedo ha realizar los siguientes pasos:

# Configurarando el Git desde la terminal
Configuramos con los comandos:
 `git config user.name "thunder609"`
 `git config  user.mail thunder609@academiagit.com` 
 
 ![comando1 nuevo](acad1.png)<br>
 
# Creacion de Directorios y archivos del aplicativo
    Pasos para crear carpetas en mi directorio Documentos por consola
1. `/AcademiaGeek-ejercicio-uno$ mkdir AcademiaGeek-ejercicio-uno. `
 
  ![comando1 nuevo](git-mkdir.png)<br>
  
2.  buscar la carpeta de trabajo por la terminal con el comando `cd`  ` /AcademiaGeek-ejercicio-uno$ cd AcademiaGeek-ejercicio-uno.` 
  
   ![comando1 nuevo](git1.png)<br>
   
3.  Con este conmando se crea las las carpetas de vercionado del proyecto    
   
   ![comando1 nuevo](git-init.png)<br>   
   
 
   
4. Estando en la carpeta ejercicio-uno crear un archivo con el nombre index.html y otro README.md con la siguiente estructura
touch index.html README.md

![comando1 nuevo](git3.png)<br>

```html 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <H1> prueba</H1>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Odio, quae iure? Adipisci saepe voluptatibus dolorum! Excepturi, quam voluptate voluptatem quibusdam rerum eum, odit soluta necessitatibus animi, vel tenetur dolorum laudantium?
        <img src="git1.png">
    </p>
</body>
/html
```


5. Crear un archivo README.md con la descripción de los conceptos aprendido en esta sesión
 Hacer un `git status` de los cambios realizados AcademiaGeek-ejercicio-uno$ git status 
En la rama master
Archivos sin seguimiento:
  (usa "git add <archivo>..." para icluirlo a lo que se será confirmado)

        README.MD

6. Agregar los archivos con git ```add .```los archivos modificados
 
![comando1 nuev1](git10.png)<br>

7. Verificar los archivos adicionados con ```git status```
![comando1 nuevo](git8.png)<br> 
 
8. Hacer un commit: git commit -m "Ejercicios Git":
 
![comando1 nuevo](git13.png)<br> 
 

 
9. Crear un repositorio en gitHub .antes ya debe crear tu usuario.
 
 
10. Agregar la url del repositorio remoto con el siguiente comando : `con el comando git remote add origin url`
`git remote add origin https://github.com/thunder609/AcademiaGeek-ejercicio-uno.git`
  en mi caso es el siguiente :
 
![comando1 nuevo](git6.png)<br>
 
11. terminar con ```git push``` para entregar los cambios a la respectiva rama.
```$ git push origin master```
 
![comando1 nuevo](git9.png)<br>
 
 
12. En este paso si es la primera vez de conectar tu terminal con ~```gitHud``` te pedira contraseña o la sincronizacion si usa la terminal de Visual Studio Code

## Entrega de la tarea

Para realizar la entrega de esta actividad debe realizar los siguientes pasos:

    1. Crear un Issues llamado Entrega-Modulo-0-01-primeros-pasos-Tarea-01
    2. Al Issues adicionar un pantallazo con el enunciado de la tarea
    3. Luego debes agregar la descripción de los pasos que ejecutaste para dar solución a la tarea y adjuntar las imágenes de evidencia.
