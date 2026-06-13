<div align="center">
  <div style="display: inline-flex; align-items: center; gap: 30px;">
    <img src="https://angular.io/assets/images/logos/angular/angular.svg" width="120" alt="Angular Logo">
    <img src="https://nodejs.org/static/images/logo.svg" width="130" alt="Node.js">
    <img src="https://cdn.worldvectorlogo.com/logos/prisma-2.svg" width="110" alt="Prisma">
  </div>
</div>

# TaskFlow

Aplicación web Full Stack inspirada en Trello, desarrollada con **Angular**, **Node.js**, **Express**, **Prisma ORM** y **PostgreSQL (Supabase)**. La plataforma permite a los usuarios organizar tareas mediante tableros y notas dinámicas, utilizando una interfaz intuitiva basada en arrastrar y soltar (Drag & Drop).

El proyecto incorpora autenticación mediante JWT, control de acceso por roles, panel administrativo y un sistema de compras simulado con fines educativos.

---

## Características

### Funcionalidades de usuario

- Registro e inicio de sesión de usuarios.
- Autenticación mediante JWT.
- Creación, edición y eliminación de tableros.
- Creación, edición y eliminación de notas.
- Organización de tareas mediante Drag & Drop.
- Movimiento de notas entre columnas/tableros.
- Sistema de carrito de compras simulado.
- Gestión de pedidos simulados.
- Interfaz dinámica desarrollada en Angular.

### Funcionalidades de administrador

- Acceso restringido mediante roles (User / Admin).
- Rutas protegidas para administradores.
- Panel administrativo completo.
- Gestión de usuarios.
- Gestión de tableros.
- Supervisión de pedidos y pagos simulados.
- Búsqueda, filtrado y administración de datos.

---

## Autenticación y seguridad

- Autenticación basada en **JSON Web Tokens (JWT)**.
- Protección de rutas en Angular mediante Guards.
- Middleware de autenticación en Express.
- Control de acceso basado en roles (User / Admin).
- Validación y sanitización de datos.
- Gestión segura de sesiones mediante tokens.

---

## Arquitectura

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

### Base de datos

- PostgreSQL
- Supabase

---

## Tecnologías utilizadas

| Capa | Tecnologías |
|------|-------------|
| Frontend | Angular, TypeScript, Angular CDK, RxJS |
| Backend | Node.js, Express.js, Prisma ORM |
| Base de datos | PostgreSQL, Supabase |
| Autenticación | JWT (JSON Web Tokens) |
| Arquitectura | REST API |

---

## Flujo de trabajo

1. El usuario se registra o inicia sesión.
2. Se le asigna un token JWT para autenticación.
3. Puede crear y gestionar tableros personales.
4. Dentro de cada tablero puede crear notas/tareas.
5. Las tareas se organizan mediante Drag & Drop.
6. El usuario puede acceder al carrito de compras simulado.
7. Los administradores gestionan usuarios, tableros y datos desde el panel.

---

## Proyecto académico

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

## Aviso

El sistema de compras incluido es únicamente simulado y no utiliza pasarelas de pago reales ni procesa transacciones económicas.
