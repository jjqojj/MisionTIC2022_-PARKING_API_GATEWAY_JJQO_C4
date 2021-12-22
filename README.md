# MisionTIC2022_-PARKING_API_GATEWAY_JJQO_C4
Programa – Program: Diplomado en Programación – Misión TIC 2022 - Ministerio de las Tecnologías de la Información y Comunicación de Colombia. Universidad Nacional de Colombia. Diploma in Programming - TIC Mission 2022 - Ministry of Information and Communication Technologies of Colombia. National University of Colombia. 

Description:

Project related to the administration of a parking lot, developed under a microservices architecture. In this case, the software system was divided into two microservices.

Microservice 1, of REST type, is in charge of implementing the functionalities that the authentication data works with. It was developed under the Python language and the Django Framework. Data persistence is supported under the PostgresSQL relational database. Microservice 2, of the REST type, is in charge of managing and billing the parking service used by users. It was implemented under the Java language and the SpringBoot Framework. Data persistence is supported by the non-relational MongoDB database. For the reception of requests and redirection of the microservices, an API Gateway of GraphQL type was developed, implemented with the JavaScript language together with the Apollo Framework. All deployments were generated on the Heroku PassS platform through Docker containers. 

The two microservices and the API Gateway make up the Backend of the project. Regarding the Frontend, a user interface was developed through the Vue.js Framework, where HTML, CSS and JavaScript were used to create each of the views. 

Descripción: Proyecto relacionado a la administración de un parqueadero, desarrollado bajo una arquitectura de microservicios.  En este caso, el sistema de software  fue dividido en dos microservicios. 

El microservicio 1, de tipo REST, está encargado  en implementar las funcionalidades que trabajan los datos de autentificación. Se desarrolló bajo lenguaje Python y el Framework Django. La persistencia de los datos está soportada bajo la base de datos relacional PostgresSQL. El microservicio 2, de tipo REST, está encargado en gestionar y facturar el servicio de parqueadero utilizado por los usuarios. Se implementó bajo el lenguaje Java y el Framework SpringBoot. La persistencia de los datos tiene como soporte la base de datos no relacional MongoDB.  Para la recepción de solicitudes y redireccionamiento de los microservicios se desarrolló un API Gateway de tipo GraphQL, implementado con el lenguaje JavaScript junto al Framework Apollo. Todos los despliegues se generaron en la plataforma Heroku PassS por medio de contenedores Docker.

Los dos microservicios y el  API Gateway conforman el Backend del proyecto. Respecto al Frontend, se desarrolló una interfaz de usuario a través del Framework Vue.js, donde se usó HTML, CSS y JavaScript para la elaboración de cada una de las vistas.
