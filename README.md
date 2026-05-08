# StayHub
**Versión Actual: v1.0.0 (Estable)**

StayHub es una plataforma de gestión de alojamientos y reservas basada en una **arquitectura de microservicios escalable**, desarrollada con **Java, Spring Boot y React**. El sistema permite una gestión dinámica de roles (Invitado, Usuario y Propietario), ofreciendo una experiencia de usuario fluida y una comunicación de alta eficiencia entre servicios mediante **gRPC**.

## Descripción

StayHub es un proyecto personal orientado al aprendizaje y diseño de arquitectura backend, desarrollado con SprinBoot y basado en microservicios independientes

El objetivo de este proyecto es simular un entorno real de gestión de alojamientos y reservas, siguiendo buenas prácticas, separación de responsabilidades y comunicación entre servicios

## Microservicios

| Servicio | Descripcion | Repositorio |
|----------|-------------|-------------|
| StayHub-Accommodation | Gestion de alojamientos | [Ver repositorio](https://github.com/Angelh0/StayHub-Accommodation) |
| StayHub-Reservation | Gestion de reservas | [Ver repositorio](https://github.com/Angelh0/StayHub-Reservation) |
| StayHub-User | Gestion de usuarios | [Ver repositorio](https://github.com/Angelh0/StayHub-User) |
| StayHub-Country | Gestión de países | [Ver repositorio](https://github.com/Angelh0/StayHub-Country) |
| StayHub-FrontEnd | Interfaz de usuario | [Ver repositorio](https://github.com/Angelh0/StayHub-FrontEnd) |


## 🛠️ Stack Tecnológico

### 🖥️ Frontend
* **Core:** React.js, JavaScript, Vue.js.
* **Estilizado:** Tailwind CSS (Diseño responsive y moderno).
* **Gestión de Medios:** Integración con Cloudinary API para gestión de imágenes.

### ⚙️ Backend 
* **Framework Principal:** Java con Spring Boot.
* **Seguridad:** Spring Security & JWT (JSON Web Tokens) para autenticación basada en roles.
* **Comunicación:** gRPC & Protocol Buffers (Comunicación interna) y REST API (Consumo externo).

### 🗄️ Persistencia y Datos
* **Bases de Datos:** PostgreSQL (Producción), H2 (Entorno de desarrollo).
* **ORM:** JPA / Hibernate para el mapeo de entidades y gestión de persistencia.

### 🚀 DevOps y Herramientas
* **Contenerización:** Docker & Docker Compose para orquestación de servicios.
* **Control de Versiones:** Git & GitHub.
* **Testing de APIs:** Postman.

---

## 🚀 Próximos Pasos
Gracias a la arquitectura y el diseño optimizado para futuras implementacinoes permitiendo que StayHub sea un proyecto escalable, se incorporarán futuras mejoras como: 
- Implementación de sistema de pagos.
- Posibilidad de añadir un alojamiento como favorito.
- Reseñas de alojammientos.
Entre otras mejoras que serán añadidas progresivamente.
