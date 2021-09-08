# TallerClientesNetworking
## Taller Arep 7 de septiembre del 2021

## Prerrequisitos
- Git version 2.25.1
- Apavhe Maven version 4.0.0
- Java version 11.0.11
- Para verificar que esten instalados los programas puede usar los suguientes comandos + mvn --version + git version
- +java --version

## Ejercicio 1
Escriba un programa en el cual usted cree un objeto URL e imprima en pantalla cada uno de los componentes de una URL. 
Es decir , debe usar los siguientes métodos: getProtocol, getAuthority, getHost, getPort, getPath, getQuery, getFile, 
getRef. Asegúrese que ninguno imprima una cadena vacía, esto implica que la URL que use para su objeto debe contener
datos suficientes.

<img width="226" alt="fotp1" src="https://user-images.githubusercontent.com/60073527/132410432-69af9f6b-dfc7-40cc-a8d8-9547cf4ebf58.PNG">


## Ejercicio 2
Escriba una aplicación browser que dada una URL lea datos de esa dirección y que los almacene en un archivo con el 
nombre resultado.html. Intente ver este archivo en el navegador. Su implementación debe ser un programa que reciba 
el parámetro de URL por medio de la línea de comandos.

<img width="512" alt="foto2" src="https://user-images.githubusercontent.com/60073527/132410480-ea9ed810-be88-4ff5-ad23-c0159170dca1.PNG">


## Ejercicio 3
Usando sockets escriba un servidor que reciba un número y responda el cuadrado de este número. Escriba un cliente 
para probarlo y envíele una secuencia de 20 números.Primero se deje ejecutar el EchoServer dos y luego de este 
eñ EchoClient2 y aca escribimeros los numero.

<img width="324" alt="foto3" src="https://user-images.githubusercontent.com/60073527/132410511-cc28a68c-9ff3-496f-9134-bc62564dedb9.PNG">

<img width="112" alt="foto4" src="https://user-images.githubusercontent.com/60073527/132410541-10c2b249-19f9-4462-a2ef-dcecf54d2de8.PNG">


## Reto 1
Escriba un servidor web que soporte múlltiples solicitudes seguidas (no concurrentes). El servidor debe retornar
todos los archivos solicitados, incluyendo páginas html e imágenes. Construya un sitio web con javascript para probar
su servidor. Despliegue su solución en Heroku. NO use frameworks web como Spark o Spring use solo Java y las librerías
para manejo de la red.
vamos a ejecutar el index.htm y este nos redirecciona abrimos nuetro navegador y corremos en el puerto : http://localhost:35000/index.html
donde nos muestra esta imagen 
<img width="950" alt="foto6" src="https://user-images.githubusercontent.com/60073527/132437102-97787813-c552-474a-92e2-4967e82fe55e.PNG">



Link de Heoku para ver la implementacion de este ejercicio:


## Instrucciones de uso
Java versión: 1.8.0
Ejecución
En el sigiente lik de Github [https://github.com/2146013/TallerClientesNetworking.git]

podras encontara la aplicacion de Clientes networking este taller nos ayuda a ver los difentes conceptos e implementaciones
clientes y servicios para correr este taller  puden usara mvn spring-boot:run,se abrira la ventana donde puede evidenciar una imagen.


El tablero se corre en http://localhost:35000/index.html

## Tecnologias

Maven
Java
Springboot
Heroku
React
P5.js

## Autor
Laura Daniela Pachon Cuan - Fecha: 07/09/2021

## Licencia
This project is licensed under the MIT License - see the LICENSE file for details
