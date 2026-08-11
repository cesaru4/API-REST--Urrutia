<div align="center">

# 🔐 API REST — Urrutia
### *Sistema de Autenticación JWT, Control de Acceso basado en Roles (RBAC) y Seguridad Backend*

[![Node.js](https://img.shields.io/badge/Node.js-v18.x-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)](https://nodejs.org/)
[![Express.js](https://img.shields.io/badge/Express.js-v4.x-000000?style=for-the-badge&logo=express&logoColor=white)](https://expressjs.com/)
[![JWT](https://img.shields.io/badge/JWT-JSON_Web_Tokens-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)](https://jwt.io/)
[![Swagger](https://img.shields.io/badge/Swagger-UI_Docs-85EA2D?style=for-the-badge&logo=swagger&logoColor=black)](https://swagger.io/)
[![Postman](https://img.shields.io/badge/Postman-Tested-FF6C37?style=for-the-badge&logo=postman&logoColor=white)](https://www.postman.com/)
[![License](https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge)](./LICENSE)

---

<p align="center">
  <a href="#-descripción">Descripción</a> •
  <a href="#-características">Características</a> •
  <a href="#-tecnologías-utilizadas">Tecnologías</a> •
  <a href="#-arquitectura">Arquitectura</a> •
  <a href="#-instalación">Instalación</a> •
  <a href="#-endpoints">Endpoints</a> •
  <a href="#-documentación-swagger">Swagger</a>
</p>

</div>

---

## 📖 Descripción

Esta aplicación es una **API REST profesional y robusta** desarrollada con **Node.js** y **Express**, diseñada para resolver de manera integral la gestión de usuarios, procesos de autenticación e identificación mediante **JSON Web Tokens (JWT)**.

La solución fue construida bajo los más altos estándares de desarrollo backend, implementando:
* 🛡️ Cifrado unidireccional de contraseñas (`bcrypt`).
* 👥 Control de acceso granular por Roles y Permisos (RBAC).
* 🧪 Validación estricta de datos de entrada y sanitización.
* 💥 Manejo de excepciones y errores de forma centralizada.
* 📄 Documentación interactiva en vivo con **Swagger UI**.

---

## 🎯 Objetivo

Desarrollar un componente de seguridad reutilizable, escalable y mantenible que sirva como núcleo para proyectos que demanden:

* Registro e inicio de sesión con token persistente.
* Almacenamiento seguro de credenciales.
* Protección de rutas críticas mediante middlewares personalizados.
* Administración centralizada del ciclo de vida de los usuarios (CRUD).
* Auto-documentación de servicios web de fácil integración.

---

## 🚀 Características

| Categoría | Funcionalidad Implementada | Estado |
| :--- | :--- | :---: |
| **Seguridad** | Cifrado de credenciales con `bcrypt` | `✅ Listo` |
| **Autenticación** | Login / Signup con emisión de tokens JWT | `✅ Listo` |
| **Autorización** | Control de Acceso Basado en Roles (RBAC) | `✅ Listo` |
| **Middlewares** | Capa de verificación de token y permisos | `✅ Listo` |
| **Recursos** | CRUD completo para el recurso Usuarios | `✅ Listo` |
| **Calidad** | Manejo global de excepciones y validaciones | `✅ Listo` |
| **Documentación**| Interfaz interactiva de API con Swagger UI | `✅ Listo` |
| **Pruebas** | Colección oficial de Postman incluida | `✅ Listo` |

---

## 🛠 Tecnologías Utilizadas

```text
  🟩 Node.js      ───► Entorno de ejecución en servidor
  ⚡ Express.js   ───► Framework web minimalista y flexible
  🔑 JWT          ───► Estándar abierto para autenticación por tokens
  🔒 bcrypt       ───► Algoritmo de encriptado de contraseñas
  📄 Swagger UI   ───► Documentación interactiva OpenAPI 3.0
  🚀 Postman      ───► Suite de pruebas para endpoints HTTP
  🐙 GitHub       ───► Control de versiones y colaboración
