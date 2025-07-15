# Task Manager - Backend 📝

Este es el backend de un gestor de tareas (Task Manager) desarrollado con **Java** y **Spring Boot**. Expone una API RESTful que permite crear, leer y eliminar tareas, usando JPA para persistencia de datos.

## 🚀 Tecnologías

- Java 17+
- Spring Boot
- Spring Web
- Spring Data JPA
- H2 Database (modo local)
- Maven

## 📁 Estructura del Proyecto
src/
└── main/
├── java/
│ └── com.jose.taskmanager/
│ ├── Task.java
│ ├── TaskRepository.java
│ ├── TaskController.java
│ └── TaskmanagerApplication.java
└── resources/
└── application.properties

## 📌 Endpoints principales

| Método | Endpoint            | Descripción                    |
|--------|---------------------|--------------------------------|
| GET    | `/api/tasks`        | Obtener todas las tareas       |
| POST   | `/api/tasks`        | Crear una nueva tarea          |
| DELETE | `/api/tasks/{id}`   | Eliminar una tarea por su ID   |

---

## 🚀 Cómo correrlo localmente

```bash
# Clonar el repositorio
git clone https://github.com/josevc274/taskmanager-backend.git
cd taskmanager-backend

# Ejecutar el proyecto
./mvnw.cmd spring-boot:run
🧪 Base de datos H2
La app se conecta automáticamente a una base de datos en memoria.

URL: http://localhost:8080/h2-console

JDBC URL: jdbc:h2:mem:testdb

Usuario: sa

Contraseña: (vacía)

👨‍💻 Autor
Jose V.
GitHub

