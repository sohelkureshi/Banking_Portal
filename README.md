### Banking Portal

A comprehensive full-stack online banking application featuring a modern frontend built with React and Redux, and a robust backend powered by Java Spring Boot. This project is organized for easy development, testing, and deployment.

---

## Project Structure

```
Banking_portal/
│
├── frontend_react_redux/    # React + Redux frontend
│
└── backend_spring_boot/     # Java Spring Boot backend
```

---

## Features

- User registration and login
- View account history and details
- Open new accounts
- Transfer funds between accounts
- Deposit and withdraw money
- Make payments
- Dynamic, self-updating charts to visualize account flows
- Responsive Material UI design
- Seamless communication with the backend API using Redux Thunk

---

## Technologies Used

- **Frontend:** React, Redux, Redux Thunk, React Router DOM, Material UI
- **Backend:** Java, Spring Boot, REST API
- **Other:** JWT authentication, CORS policy management, Cookies

---

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/sohelkureshi/Banking_portal
cd Banking_portal
```

---

### 2. Frontend Setup

```bash
cd frontend_react_redux
npm install
npm run start
```

- The frontend will be available at [http://localhost:3000](http://localhost:3000).

---

### 3. Backend Setup

```bash
cd backend_spring_boot
```

#### Configure your database

- Ensure you have a MySQL (or your preferred relational) database running.
- Update the `application.properties` (or `application.yml`) file with your database connection details (URL, username, password, driver class, etc.).

#### Build and Run the Spring Boot Application

- If you are using Maven, run:
  ```bash
  ./mvnw spring-boot:run
  ```
  or
  ```bash
  mvn spring-boot:run
  ```
- If you are using Gradle, run:
  ```bash
  ./gradlew bootRun
  ```
  or
  ```bash
  gradle bootRun
  ```
- Alternatively, you can build the JAR and run it directly:
  ```bash
  mvn clean package
  java -jar target/*.jar
  ```

- The backend server will start at [http://localhost:8080](http://localhost:8080).


*(Add screenshots in this section to showcase the UI and features.)*

---

## Lessons and Concepts

- Advanced React and Redux patterns for scalable state management
- Integration of Redux Thunk for asynchronous operations
- Secure communication with backend using JWT and cookies
- Material UI for responsive, modern interfaces
- Handling CORS policies and backend integration
- Real-time updates and SPA architecture

---

## Author

Designed and developed by [@sohelkureshi](https://github.com/sohelkureshi).

---

Feel free to explore the project, contribute, or reach out for any questions!