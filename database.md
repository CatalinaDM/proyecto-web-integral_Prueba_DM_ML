# Documentación de la Base de Datos: FreeFinance

## 1. Descripción General
Este documento contiene la estructura, configuración y detalles de la base de datos principal para la aplicación FreeFinance.

## 2. Tecnologías
* **Motor de Base de Datos:** PostgreSQL / MongoDB *(borrar el que no aplique)*
* **Entorno:** Desarrollo / Producción
* **ORM / ODM:** TypeORM / Mongoose / SQLAlchemy

## 3. Variables de Entorno (.env)
Para conectar el backend (ej. NestJS o Flask) con la base de datos, asegúrate de configurar las siguientes variables de entorno:

```env
DB_HOST=localhost
DB_PORT=5432  # o 27017 para MongoDB
DB_USER=tu_usuario
DB_PASSWORD=tu_contraseña
DB_NAME=freefinance_db