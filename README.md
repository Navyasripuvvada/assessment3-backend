# Multi-Agent Helpdesk Ticketing System

A backend API for a multi-agent helpdesk ticketing system built with **NestJS, MongoDB, JWT authentication, and role-based access control (RBAC)**.

## Tech Stack

* **Node.js**
* **NestJS**
* **TypeScript**
* **MongoDB**
* **Mongoose**
* **JWT Authentication**
* **Role-Based Access Control (RBAC)**
* **Swagger / OpenAPI**
* **Class Validator**
* **bcrypt**
* **NestJS Schedule**

## Features

### Authentication

* User registration
* User login
* JWT-based authentication
* Password hashing using bcrypt
* Protected API routes

### Role-Based Access Control

The system supports different user roles and restricts access to APIs based on permissions.

### Ticket Management

* Create tickets
* View tickets
* Update tickets
* Ticket status management
* Ticket assignment
* Ticket priority handling

### API Documentation

Swagger is available for testing and exploring the APIs.

## Project Structure

```text
src/
├── auth/
│   ├── decorators/
│   ├── dto/
│   ├── guards/
│   ├── interface/
│   ├── auth.controller.ts
│   ├── auth.module.ts
│   └── auth.service.ts
│
├── database/
│   └── seed.ts
│
├── tickets/
│   ├── dto/
│   ├── schemas/
│   ├── ticket.controller.ts
│   ├── ticket.module.ts
│   └── ticket.service.ts
│
├── users/
│   ├── schemas/
│   ├── user.module.ts
│   └── user.service.ts
│
├── app.controller.ts
├── app.module.ts
├── app.service.ts
└── main.ts
```

## Installation

Clone the repository:

```bash
git clone https://github.com/Navyasripuvvada/assessment3-backend.git
```

Go to the project directory:

```bash
cd assessment3-backend/assessment3-backend
```

Install d
