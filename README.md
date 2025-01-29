# API REST de Gestión de Usuarios

![Node.js](https://img.shields.io/badge/Node.js-18.x-green)
![Express](https://img.shields.io/badge/Express-4.x-lightgrey)
![License](https://img.shields.io/badge/License-MIT-blue)

Aplicación web para gestión de usuarios con API RESTful y interfaz frontend básica.

## 📋 Descripción
Proyecto desarrollado como parte del módulo de Despliegue de Aplicaciones Web. Incluye:
- Backend con Node.js/Express
- Frontend básico con HTML/CSS
- Sistema de registro de peticiones HTTP
- Gestión de usuarios CRUD

## ✨ Características principales
- **Registro de peticiones HTTP**: Middleware para log de todas las solicitudes
- **Autenticación JWT**: Sistema básico de autenticación
- **API RESTful**: 
  - GET /users - Listar todos los usuarios
  - POST /users - Crear nuevo usuario
  - PUT /users/:id - Actualizar usuario
  - DELETE /users/:id - Eliminar usuario
- **Interfaz web responsive**
- Configuración por variables de entorno

## 🚀 Instalación

1. Clonar repositorio:
```bash
git clone https://github.com/tu-usuario/api-rest-users.git
cd api-rest-users