# Mi Turno - Digitalizá tu agenda, maximizá tu tiempo

## Descripción General

**Mi Turno** es un sistema diseñado como un hub de negocios que permite a pequeñas y medianas empresas centralizarse en una plataforma única. Esto permite que los clientes puedan reservar turnos fácilmente en diferentes negocios desde un mismo lugar. El sistema está orientado tanto a facilitar la vida de los usuarios como a optimizar la gestión interna de los negocios.

El propósito principal de este sistema es ofrecer una solución integral para la gestión de reservas, cancelaciones, servicios y profesionales. Cada negocio puede configurar su propio catálogo de servicios y gestionar los horarios de sus profesionales de manera individual, proporcionando una flexibilidad completa para adaptarse a las necesidades específicas de cada empresa. Además, permite a los clientes acceder de forma sencilla a la oferta disponible, facilitando la organización y la comunicación entre ambas partes.

### Público objetivo
- **Negocios**: Está dirigido a pequeños y medianos negocios que necesitan una herramienta eficiente para gestionar turnos y optimizar sus servicios.
- **Clientes**: También está diseñado para usuarios que deseen encontrar y reservar turnos fácilmente en cualquiera de los negocios registrados dentro del hub.

---

## Estructura de la Organización

El proyecto está compuesto por dos repositorios principales, que trabajan en conjunto para ofrecer una solución completa:

1. **[Mi Turno Frontend](https://github.com/Mi-turno/mi-turno-frontend)**  
   Este repositorio contiene la aplicación web, que incluye la interfaz de usuario y toda la lógica del cliente.

2. **[Mi Turno Backend](https://github.com/Mi-turno/mi-turno-backend)**  
   Aquí se encuentra el servidor, que gestiona la lógica de negocio, la base de datos y las APIs REST necesarias para el funcionamiento del sistema.

Ambos repositorios están diseñados para trabajar juntos, ofreciendo una experiencia integrada que cubre todas las necesidades del sistema, desde la interacción con el cliente hasta el manejo interno de los datos.

---

## Tecnologías Utilizadas

- **Planeación**:
  - Jira: Gestión de tareas (SCRUM)
  - Miro: Diseño de interfaces y diagramas
  - Github: Gestión de versiones
  - Discord: Comuniación
   
- **Frontend**:  
  - HTML, CSS y TypeScript.  
  - Framework: Angular.

- **Backend**:  
  - Lenguaje: Java.  
  - Frameworks: Spring Boot (con Spring Data, Spring Security y Spring Mail).

- **Base de Datos**:  
  - MySQL.

---

## Guía Básica de Instalación

### Requisitos previos
Antes de comenzar, asegúrate de tener instaladas las siguientes herramientas:
- **Node.js** y **Angular 18 CLI** para ejecutar el frontend.
- **Java JDK** (versión 11 o superior) y **Maven** para el backend.
- **MySQL** para la base de datos.

### Pasos para instalar el proyecto
1. Clona los repositorios del frontend y backend:
   ```bash
   git clone https://github.com/organizacion/mi-turno-frontend.git
   git clone https://github.com/organizacion/mi-turno-backend.git


### Configura la base de datos:

1. Crea una base de datos en MySQL llamada `mi_turno` (o el nombre configurado en el backend).
2. Configura las credenciales de acceso en el archivo `application.properties` del backend.

### Instala y ejecuta el backend:

1. Ve al directorio del backend:
   ```bash
   cd mi-turno-backend
2. Compila y ejecuta el servidor
   ./mvnw spring-boot:run
   
### Instala y ejecuta el frontend

1. Ve al directorio del frontend
   cd mi-turno-frontend
2. Instala las dependencias
   npm install
3. Ejecuta la aplicación:
   ng serve

---

### Asegúrate de que ambos repositorios estén corriendo simultáneamente

- El **frontend** estará disponible en [http://localhost:4200](http://localhost:4200).
- El **backend** estará corriendo en [http://localhost:8080](http://localhost:8080).
   
