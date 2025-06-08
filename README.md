# 🎮 Backend para E-commerce "Ez4gamers"

Este es el corazón de la plataforma de e-commerce "Ez4gamers". Un backend robusto construido con Java y Spring Boot, diseñado para manejar toda la lógica de negocio, desde el catálogo de productos hasta la gestión de usuarios.

> **Objetivo**: Proveer una API RESTful segura, escalable y eficiente para que una aplicación cliente (frontend) pueda consumir los datos y realizar operaciones.

### 🛠️ Tecnologías Utilizadas

* **Java 11+**: Lenguaje principal de la aplicación.
* **Spring Boot**: Framework para la creación rápida de aplicaciones.
* **Spring Web**: Para la construcción de los endpoints de la API REST.
* **Spring Data JPA**: Para la persistencia de datos y comunicación con la base de datos.
* **Spring Security**: Para la gestión de autenticación y autorización.
* **Maven**: Como gestor de dependencias y construcción del proyecto.

### Cómo ponerlo en marcha

1.  **Clonar el repositorio**: `git clone https://github.com/Russtels/E-comerce-Ez4gamers.git`
2.  **Configurar la base de datos**: Modifica el archivo `src/main/resources/application.properties` con tus credenciales de base de datos.
3.  **Ejecutar**: Utiliza Maven para lanzar la aplicación.

    ```bash
    mvn spring-boot:run
    ```
