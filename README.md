# Castro's Libros Marketplace - Backend

Este repositorio contiene la parte backend para el Castro's Libros Marketplace, proporcionando la lógica del servidor y la gestión de la librería.

## Descripción

Este proyecto se enfoca en brindar funcionalidades de servidor para respaldar el ecommerce de libros y el mantenedor de la librería del Castro's Libros Marketplace.

## Funcionalidades Principales

- **API Restful:** Proporciona endpoints para la gestión de libros, usuarios y autenticación.
- **Seguridad:** Utiliza JWT para autenticación y autorización.
- **Middleware de Logging:** Integración de Morgan para el registro de solicitudes HTTP.
- **Interacción con Base de Datos:** Utiliza PostgreSQL como base de datos principal.
- **Documentación API:** Utiliza Swagger para documentar los endpoints de la API.

## Tecnologías Utilizadas

- Express.js
- JWT (jsonwebtoken)
- Bcrypt.js
- CORS
- Morgan
- Multer
- PostgreSQL (pg)
- Dotenv
- Swagger-jsdoc
- Swagger-ui-express

## Scripts Disponibles

- `npm start`: Inicia el servidor en modo de producción.
- `npm run dev`: Inicia el servidor con nodemon para desarrollo.
- `npm test`: Ejecuta pruebas utilizando Jest y Supertest.

## Instalación

1. Clona el repositorio: `git clone https://github.com/NeaCS/Librer-a-Castro-Backend.git`
2. Instala las dependencias: `npm install`

## Configuración

1. Crea un archivo `.env` basado en el archivo `.env.example` proporcionado.
2. Configura las variables de entorno necesarias, como la conexión a la base de datos y las claves secretas.

## Uso

- Ejecuta `npm start` para iniciar el servidor en modo de producción.
- Para el desarrollo, usa `npm run dev` para iniciar el servidor con nodemon.



---
Si tienes alguna pregunta, no dudes en contactar al equipo de desarrollo.
