<p align="center">
  <img src="https://angular.io/assets/images/logos/angular/angular.svg" width="120" alt="Angular Logo">
  &nbsp;&nbsp;&nbsp;
  <img src="https://upload.wikimedia.org/wikipedia/commons/d/d9/Node.js_logo.svg" width="120" alt="Node Logo">
</p>

# TaskFlow

Aplicación web Full Stack inspirada en Trello, desarrollada con **Angular**, **Node.js**, **Express**, **Prisma ORM** y **PostgreSQL (Supabase)**. La plataforma permite a los usuarios organizar tareas mediante tableros y notas dinámicas, utilizando una interfaz intuitiva basada en arrastrar y soltar (Drag & Drop).

El proyecto incorpora autenticación mediante JWT, control de acceso por roles, panel administrativo y un sistema de compras simulado con fines educativos.

---

## Features

### User Features

- Registro e inicio de sesión de usuarios.
- Autenticación mediante JWT.
- Creación, edición y eliminación de tableros.
- Creación, edición y eliminación de notas.
- Organización de tareas mediante Drag & Drop.
- Movimiento de notas entre columnas/tableros.
- Sistema de carrito de compras simulado.
- Gestión de pedidos simulados.
- Interfaz dinámica desarrollada en Angular.

### Admin Features

- Acceso restringido mediante roles (User / Admin).
- Rutas protegidas para administradores.
- Panel administrativo completo.
- Gestión de usuarios.
- Gestión de tableros.
- Supervisión de pedidos y pagos simulados.
- Búsqueda, filtrado y administración de datos.

---

## Authentication & Security

- Autenticación basada en **JSON Web Tokens (JWT)**.
- Protección de rutas en Angular mediante Guards.
- Middleware de autenticación en Express.
- Control de acceso basado en roles (User / Admin).
- Validación y sanitización de datos.
- Gestión segura de sesiones mediante tokens.

---

## Architecture

### Frontend

- Angular
- TypeScript
- Angular Router
- Angular CDK Drag & Drop
- RxJS
- Guards de autenticación

### Backend

- Node.js
- Express.js
- Prisma ORM
- REST API
- JWT Authentication Middleware

### Database

- PostgreSQL
- Supabase

---

## Technologies Used

| Layer | Technologies |
|------|-------------|
| Frontend | Angular, TypeScript, Angular CDK, RxJS |
| Backend | Node.js, Express.js, Prisma ORM |
| Database | PostgreSQL, Supabase |
| Authentication | JWT (JSON Web Tokens) |
| Architecture | REST API |

---

## Workflow

1. El usuario se registra o inicia sesión.
2. Se le asigna un token JWT para autenticación.
3. Puede crear y gestionar tableros personales.
4. Dentro de cada tablero puede crear notas/tareas.
5. Las tareas se organizan mediante Drag & Drop.
6. El usuario puede acceder al carrito de compras simulado.
7. Los administradores gestionan usuarios, tableros y datos desde el panel.

---

## Academic Project

Este proyecto fue desarrollado como parte de un trabajo académico del ciclo formativo de **Desarrollo de Aplicaciones Web (DAW)**.

El objetivo principal era aplicar conocimientos de desarrollo Full Stack mediante la construcción de una aplicación web completa utilizando tecnologías modernas tanto en frontend como en backend.

Durante el desarrollo se trabajaron conceptos como:

- Desarrollo de aplicaciones SPA con Angular.
- Diseño y consumo de APIs REST.
- Autenticación y autorización mediante JWT.
- Control de acceso basado en roles.
- Gestión de bases de datos relacionales con PostgreSQL.
- Uso de Prisma ORM.
- Implementación de Drag & Drop.
- Arquitectura cliente-servidor.
- Integración de frontend y backend.

Aunque nació como un proyecto académico, la aplicación fue diseñada siguiendo prácticas cercanas a entornos profesionales reales.

---

## Disclaimer

El sistema de compras incluido es únicamente simulado y no utiliza pasarelas de pago reales ni procesa transacciones económicas.
