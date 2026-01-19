# Servidor Eureka

Este microservicio actúa como el Service Registry (Directorio de Servicios). Utiliza **Spring Cloud Netflix Eureka** para permitir que otros microservicios (Java, FastAPI, etc.) se registren y se localicen entre sí sin necesidad de conocer sus direcciones IP fijas.

## 💻 Funcionalidades Principales

* **Auto-registro**: Los microservicios se inscriben al arrancar.
* **Monitoreo de salud**: Gestión de instancias mediante heartbeats.

## ⚡ Ejuctar el servicio

Una vez levantado, puedes acceder al panel de control en tu navegador: `http://localhost:8761`


