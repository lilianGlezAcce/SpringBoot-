# Spring Boot 

### Overview
El siguiente ejercicio, se centra en conocer la estructura de los proyectos, la anatomía de un microservicio, creación de servicios web (GET – POST – PUT - DELETE), inyección de dependencias, principales anotaciones de Spring y uso de Postman.

### Helpful Resources
¿Qué es Java Spring Boot? (IBM): https://www.ibm.com/mx-es/topics/java-spring-boot

Definición de métodos de recursos para aplicaciones RESTful (IBM): https://www.ibm.com/docs/es/was-nd/8.5.5?topic=applications-defining-resource-methods-restful

POSTMAN Guía de Instalación y funcionamiento.: https://developers.sw.com.mx/knowledge-base/guia-se-instalacion-y-funcionamiento-de-postman/

Guía de anotaciones de Spring Framework: https://mvitinnovaciontecnologica.wordpress.com/2020/02/06/guia-de-anotaciones-de-spring-framework/

#### Official Language/Framework/Library Documentation
#### Main concepts (Databases, Object Oriented Programming, Classes, Polymorphism, etc)
#### Blog articles, samples
#### Public repositories
#### Video tutorials

### Prerequisites

1. Download and install JDK 17 (at a minimum) desde este link: https://start.spring.io/
2. Download and install Spring Tool Suite for Eclipse from this link: https://spring.io/tools
3. Download and install Git from this link: https://git-scm.com/downloads
4. Download spring base project from this link : https://start.spring.io/   
 - Add dependencies: Spring Web and Lombok.
 - Project: Maven.
 - Packaging: Jar.
 - Java: 17
 - Sprng Boot : default. 

### Completion guide

#### Instructions
1. Descargar proyecto con las indicaciones de arriba.
Parte 1
2. Utilizar el siguiente video como guía para aprender las bases de la creación de servicios: https://www.youtube.com/watch?v=RfLx9RYjJA8
3. Posicionarte en la clase principal (src/main/java), dar clic izquierdo para que nos arroje el menú de opciones y seleccionar “Run ……  main()”.
4. Creación de paquetes, clases, controladores, como se exponen los servicios GET (min 27 - min 46)
5. Servico Delete (min 55 - min 60)
6. Servico Post (min 1:05:00 - min 1:10:00)
7. Servico Put (min 1:16:00 - min 1:18:00)
Parte 2
8. Utilizar el siguiente video como guía para aprender más sobre spring: https://www.youtube.com/watch?v=XVkRqueUCPQ
9. Implementación de ResponseEntity : (min 18 - min 30)
10. Inyección de dependencias: (min 49 - min 1:09:00)
11. Explicación de archivo application.properties (min 1:10:00)

Estos dos videos nos ayudan para la comprensión de microservicios, ya que nos explican la estructura del proyecto, lo que contiene el archivo pom, como utilizar las principales anotaciones de Spring, las diferencias que existen entre @Repository, @Component, @Service & @Controller, creación de servicios web y el como consumirlos.  

#### Exercise
1. Crear proyecto llamado: Juegos Olímpicos
2. Crear un Modelo con su respectiva clase : “team”
*String nombrePais
*Int medallasOro
*Int medallasPlata
*Int medallasBronce
*String deporte
 - Agregar anotaciones como @NonNull, @Data
3. Creación servicio Post, donde sea requisito agregar todos los datos del DAO
4. Creación servicio Put, donde sea posible cambiar la cantidad de medallas de los equipos
5. Creación servicio Delete, donde sea posible la eliminación de un equipo
6. Creación de varios servicios Get, ejemplo
 - Obtención de todos los equipos por país
 - Obtención de los deportes que existen dependiendo del país 

Favor de poner en práctica todo lo visto en los videos anteriores, el ejercicio deberá contener la estructura vista (@Component, @Service & @Controller), uso de inyección de dependencias, implementación de ResponseEntity, anotaciones de Spring, etc. 

#### Example
#### Testing and Validation requisites
Vaya a la clase principal de Spring y debería correr el proyecto sin ningún error, después, probar todos los servicios creados en Postman y validar que la respuesta recibida sea la correcta 

#### Expected output
Por favor, proporcione una captura de pantalla de TODOS los servicios creados con su respectiva prueba a la persona que le asignó este laboratorio.

