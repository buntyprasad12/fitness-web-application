# 🏋️ Fitness Web Application

A full-stack **Fitness Web Application** designed to help users manage their fitness activities, workouts, and related information through a simple and user-friendly web interface.

## 🚀 Features

* 🔐 User authentication and authorization
* 👤 User management
* 🏋️ Workout and fitness management
* ➕ Create fitness/workout records
* 🔍 View and manage fitness data
* ✏️ Update existing records
* 🗑️ Delete records
* 🔄 RESTful CRUD operations
* 📊 Backend API integration
* 🗄️ Database connectivity
* 🌐 Responsive web interface

## 🛠️ Technologies Used

### Backend

* **Java**
* **Spring Boot**
* **Spring MVC**
* **Spring Data JPA**
* **REST APIs**
* **Hibernate**

### Database

* **MySQL**
* **SQL**

### Frontend

* **HTML5**
* **CSS3**
* **JavaScript**
* **React.js** *(if used in your project)*

### Tools

* **Git & GitHub**
* **Maven**
* **Postman**
* **Eclipse / IntelliJ IDEA / VS Code**

## 📁 Project Structure

```text
fitness-web-project/
│
├── fitness-frontend/       # Frontend application
│
├── gateway/                # API Gateway
│
├── configserver/            # Configuration Server
│
├── eureka/                  # Service Discovery
│
├── services/                # Backend microservices
│
├── pom.xml                 # Maven configuration
│
└── README.md               # Project documentation
```

## 🔄 CRUD Operations

The application supports complete CRUD functionality:

| Operation  | Description                  |
| ---------- | ---------------------------- |
| **Create** | Add new fitness/workout data |
| **Read**   | Retrieve fitness information |
| **Update** | Modify existing records      |
| **Delete** | Remove records               |

## ⚙️ How to Run

### 1. Clone the repository

```bash
git clone https://github.com/buntyprasad12/fitness-web-project.git
```

### 2. Open the project

Open the project in **Eclipse, IntelliJ IDEA, or VS Code**.

### 3. Configure the database

Create a MySQL database and update the database configuration in the Spring Boot application's `application.properties` or `application.yml`.

Example:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/fitness_db
spring.datasource.username=root
spring.datasource.password=your_password

spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
```

### 4. Build the project

```bash
mvn clean install
```

### 5. Run the Spring Boot application

```bash
mvn spring-boot:run
```

### 6. Start the frontend

If the project uses React:

```bash
cd fitness-frontend
npm install
npm start
```

## 📌 API

The backend provides REST APIs for managing fitness-related data.

Example endpoints:

```text
GET     /api/fitness
GET     /api/fitness/{id}
POST    /api/fitness
PUT     /api/fitness/{id}
DELETE  /api/fitness/{id}
```

## 🎯 Project Objective

The main objective of this project is to develop a practical fitness management system while implementing modern software development concepts such as:

* REST API development
* CRUD operations
* Spring Boot
* Database integration
* Microservices architecture
* API Gateway
* Service Discovery
* Frontend-backend integration
* Git and GitHub version control

## 👨‍💻 Developer

**Bunty Prasad Gupta**

Java | Spring Boot | SQL | REST API | Git & GitHub

### ⭐ If you find this project useful

Feel free to **star ⭐ the repository** and explore the project.
