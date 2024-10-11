# LinkedInApp (Clone) - Professional Networking Platform

### Overview

Welcome to the LinkedInApp (Clone) project! This application is inspired by the functionalities of LinkedIn and is designed to connect professionals, allowing them to build profiles, connect with peers, and share updates. It has been developed using **Spring Boot** and follows a **RESTful API** architecture, making it scalable and efficient for handling various networking features.

### Features

- **User Registration & Authentication**  
  Users can create accounts, log in, and manage their profiles securely.
  
- **Profile Management**  
  Users can update personal details like name, bio, experience, education, and skills.

- **Connection Management**  
  Ability to connect with other users, view connections, and expand the professional network.

- **Post and Share Updates**  
  Users can create posts, share thoughts, articles, and professional updates.

- **Job Listings**  
  Job postings for users looking to recruit or seek new opportunities.

- **Notifications**  
  Receive real-time notifications for connection requests, messages, and job applications.

- **Admin Panel**  
  Admin-level access for managing users, jobs, and content moderation.

---

### Technologies Used

- **Backend**:  
  - **Spring Boot** (REST API Development)
  - **Java** (Primary language)
  - **JPA/Hibernate** (Database ORM)
  - **PostgreSQL** (Database)
  
- **Security**:  
  - **Spring Security** with JWT for authentication and authorization
  
- **API Documentation**:  
  - **Swagger/OpenAPI** integrated for easy API testing and exploration
  
- **Additional Tools**:  
  - **Postman** (for API testing)
  - **Git** (for version control)

---

### Setup Instructions

1. **Clone the Repository**  
   ```bash
   git clone https://github.com/adsingh2602/LinkedInApp.git
   ```

2. **Navigate to the project directory**  
   ```bash
   cd LinkedInApp
   ```

3. **Database Setup**  
   Make sure PostgreSQL is installed and running. Create a new database with the following details:
   ```bash
   Database Name: linkedinapp_db
   Username: <your_username>
   Password: <your_password>
   ```

4. **Configure `application.yml`**  
   Update your `src/main/resources/application.yml` file with your database details:
   ```yaml
   spring:
     datasource:
       url: jdbc:postgresql://localhost:5432/linkedinapp_db
       username: <your_username>
       password: <your_password>
   ```

5. **Run the Application**  
   Use the following command to run the application:
   ```bash
   ./mvnw spring-boot:run
   ```

6. **Swagger API Documentation**  
   Once the application is running, you can explore the APIs via Swagger UI:
   ```
   http://localhost:8080/swagger-ui.html
   ```

---

### Contributions

Feel free to contribute by forking the repository and submitting pull requests. All contributions are welcome!

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature-name`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/your-feature-name`).
5. Open a Pull Request.

---

### License

This project is licensed under the MIT License. See the `LICENSE` file for details.
