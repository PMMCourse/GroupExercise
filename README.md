# GroupExercise

Este es un ejercicio en grupo para completar en un grupo. 

Se debe realizar una arquitectura de MVVM en el proyecto, se puede tomar la decisión de completarlo ya sea con Xamarin Forms o con Xamarin Native.

Hay distintas partes del ejercicio que vamos a comentar:

## Login

![alt text](https://github.com/PMMCourse/GroupExercise/blob/master/Content/Login.gif)

Inicialmente el login se puede realizar por defecto con el usuario **master** y la contraseña **master**

Cuando se cree se podrá hacer login con él también. La aplicación debe mantener la sesión iniciada, eso quiere decir que tras cerrar la aplicación y volverla a abrir, debería llevarnos directamente a la pantalla inicial.

## Crear usuario

![alt text](https://github.com/PMMCourse/GroupExercise/blob/master/Content/CreateUser.gif)

La pantalla inicial, será una pantalla que nos mostrará todos los usuarios creados, que en el momento del arranque no habrá ninguno, obviamente y tendremos al final de la pantalla un botón que nos permitirá abrir la pantalla de creación de usuario. 

A su vez, tendremos un *Maestro detalle* donde se encuentran las opciones de:
- Mapa
- Usuarios (Que será está pantalla)
- Ajustes
- Desconexión

A su vez, en la cabecera del maestro detalle, debe aparecer un mensaje de bienvenida con el nombre del usuario.

## Detalle de usuarios

![alt text](https://github.com/PMMCourse/GroupExercise/blob/master/Content/UserDetail.gif)

Al pulsar en el listado de usuarios sobre uno de los usuarios en cuestión, accederemos al detalle. Donde podemos agregar una posición en el mapa y una imagen, usando en este caso la camara.

Al pulsar en agregar localización, volveremos a la pantalla anterior.

**Ese usuario podrá también iniciar sesión.**


## Mapa

![alt text](https://github.com/PMMCourse/GroupExercise/blob/master/Content/Maps.gif)

El mapa además de mostrar la opción de localizar el usuario, mostrara en el mismo todas las posiciones que se hayan cargado para el detalle de usuarios. Como se puede comprobar en el gif.


## Ajustes 

![alt text](https://github.com/PMMCourse/GroupExercise/blob/master/Content/Settings.gif)

La pantalla de ajustes tendrá las opciones para visualizar el mapa.

Como se puede comprobar se usa un CheckBox y al marcar una opción se desmarca la otra y viceversa.

## LogOut

![alt text](https://github.com/PMMCourse/GroupExercise/blob/master/Content/LogOut.gif)

Al pulsar en la opción de desconectar, volveremos a la pantalla de Login, en esta pantalla podremos hacer login, ya sea con el master/master inicial o con cualquier otro usuario.


El tiempo de realización del ejercicio es aproximadamente entre 15 a 20 horas. Que divididas en grupo debería ser mucho menor. Es importante realizar una correcta organización del equipo, uso de Git correctamente, etc. Se valorarán todo este tipo de detalles, además de su ejecución.



