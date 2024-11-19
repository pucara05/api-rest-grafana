# API REST con Monitoreo y Pruebas de Rendimiento 🚀

## Descripción 📋
Este proyecto es una **API RESTful** desarrollada con **Node.js**, **Sequelize** y **MySQL/PostgreSQL**. Está diseñada para gestionar usuarios y proporcionar información en tiempo real. Además, integra **pruebas de rendimiento** utilizando **K6** y un sistema de **monitoreo visual** con **Grafana** e **InfluxDB** para un análisis detallado de las métricas.

![API REST](https://img.shields.io/badge/Node.js-API--REST-brightgreen)

## Características 🛠️

- **Gestión de usuarios**: CRUD (Crear, Leer, Actualizar, Eliminar) de usuarios a través de endpoints RESTful.
- **Pruebas de rendimiento**: Uso de **K6** para realizar pruebas de carga y evaluar el rendimiento de la API.
- **Monitoreo en tiempo real**: Integración con **Grafana** e **InfluxDB** para la visualización de métricas y análisis de la aplicación.
- **Documentación Swagger**: Acceso a una documentación interactiva para explorar y probar los endpoints de la API.

## Instalación 🚧

### Prerrequisitos
Asegúrate de tener instalados los siguientes programas:
- [Node.js](https://nodejs.org/) (v16 o superior)
- [Docker](https://www.docker.com/) y [Docker Compose](https://docs.docker.com/compose/)
- [Git](https://git-scm.com/)

### Pasos para ejecutar el proyecto

1. **Clona este repositorio**:
   ```bash
   git clone https://github.com/pucara05/api-rest-grafana.git

2. Instala las dependencias: Entra en el directorio del proyecto y ejecuta:
   npm install

3. Levanta los servicios con Docker: Utiliza Docker Compose para iniciar todos los servicios necesarios:
   docker-compose up
o si usas una versión más reciente de Docker:

   docker compose up

4. Accede a la aplicación: Una vez que los servicios estén corriendo, puedes acceder a la API en:

   http://localhost:3000

   Uso 🔧
   
Endpoints disponibles

Para explorar la API y ver todos los endpoints disponibles, puedes acceder a la documentación interactiva de Swagger:

http://localhost:3000/api-docs

Realizar pruebas de rendimiento con K6

Para ejecutar pruebas de carga con K6, puedes seguir las instrucciones dentro de la carpeta src/test/k6/ para configurar y ejecutar tus scripts de prueba.


Monitoreo de la aplicación
Accede a Grafana para visualizar las métricas de rendimiento en tiempo real y obtener estadísticas detalladas sobre la API:

URL de Grafana: http://localhost:3000 (usuario: admin, contraseña: admin)

Tecnologías utilizadas 💻

Node.js: Plataforma de ejecución para JavaScript del lado del servidor.

Sequelize: ORM para Node.js que facilita la interacción con bases de datos SQL.

MySQL / PostgreSQL: Bases de datos relacionales utilizadas en este proyecto.

Docker: Contenerización de los servicios para un entorno de desarrollo y producción consistente.

Jest y Supertest: Frameworks de pruebas para realizar pruebas unitarias y de integración.

K6: Herramienta de pruebas de carga para evaluar el rendimiento de la API.

Grafana e InfluxDB: Solución de monitoreo y visualización de métricas en tiempo real.

Swagger: Documentación interactiva para explorar y probar los endpoints de la API.

Contribuciones 🤝

Si deseas contribuir al proyecto, sigue estos pasos:

Haz un fork del repositorio.
Crea una nueva rama (git checkout -b feature/nueva-funcionalidad).
Realiza tus cambios y haz commit.
Envía un pull request con una descripción clara de las modificaciones.

Licencia 📄

Este proyecto está licenciado bajo la Licencia MIT. Consulta el archivo LICENSE para más detalles.
