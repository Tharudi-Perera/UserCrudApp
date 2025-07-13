# 🌐 Full Stack User Management Application

This is a full stack user management web application developed using React.js for the frontend, Spring Boot for the backend, and MySQL as the database. 

The application enables users to perform basic CRUD operations — including creating new users, viewing a list of users, updating existing user information, and deleting users from the system. 

On the frontend, React provides a responsive and intuitive interface, allowing smooth navigation and interaction with form fields and user lists. The backend is powered by Spring Boot, which exposes a RESTful API to handle HTTP requests and perform operations using Spring Data JPA. All user data is securely stored and managed in a MySQL database. 

The application is structured with clear separation of concerns and follows a client-server architecture, making it a great demonstration of how frontend and backend technologies can work together to build scalable and maintainable software systems.

## 🚀 Tech Stack

- **Frontend**: [React.js](https://reactjs.org/)
- **Backend**: [Spring Boot](https://spring.io/projects/spring-boot)
- **Database**: [MySQL](https://www.mysql.com/)
- **API**: RESTful services using Spring Boot

## 💡 Features

- Create/Register a new user
- View all registered users in a table
- View detailed information of a single user
- Edit and update existing user details
- Delete users from the database
- Clean and responsive UI

### Backend (Spring Boot)

1. Clone the repository.
2. Navigate to the `backend` folder.
3. Update `application.properties` with your MySQL credentials.
4. Run the application using your IDE or `mvn spring-boot:run`.

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/your_db_name
spring.datasource.username=your_username
spring.datasource.password=your_password
