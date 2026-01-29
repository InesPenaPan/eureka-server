# Service Discovery
**Componente del Trabajo de Fin de Máster (TFM)** > *Máster en Ingeniería de Software y Sistemas Informáticos (MSSI)*

Este componente actúa como un servidor de *Service Discovery* basado en **Netflix Eureka**, centralizando el registro dinámico de instancias para permitir que los microservicios se localicen entre sí automáticamente.

Funcionalidades principales:

* Registro automático de nuevas instancias.
* Monitorización de salud mediante señales de vida (heartbeats).
* Resolución de nombres lógicos para localización de servicios.
* Sincronización del registro en todo el ecosistema.
* Mecanismo de autopreservación ante fallos de red.
* Interfaz gráfica para supervisión en tiempo real.


## 🛠️ Stack

El proyecto integrando las siguientes librerías:

* **Spring Cloud Netflix Eureka Server**: Dependencia principal para habilitar el registro de instancias.
* **Spring Boot Actuator**: Monitorización del estado de salud del servicio.
* **Spring Boot Starter Web**: Soporte para la interfaz web y la API del servidor.


## ⚡ Ejuctar el servicio

Una vez levantado, puedes acceder al panel de control en tu navegador: `http://localhost:8761`


