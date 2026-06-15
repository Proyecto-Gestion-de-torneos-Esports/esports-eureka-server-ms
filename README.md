# Microservicio Eureka Server
Este microservicio actúa como el directorio central de toda la arquitectura en la nube. No posee base de datos ni maneja lógica de negocio de los torneos, su función es mantener un registro en vivo de todos los microservicios encendidos y sus respectivos puertos, los microservicios pueden comunicarse entre sí llamándose por su nombre interno sin depender de direcciones IP fijas

Dependencias

* Spring Cloud Netflix Eureka Server

* Spring Boot Starter
