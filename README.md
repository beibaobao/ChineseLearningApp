# Chinese Learning Application

## Introduction

The Chinese Learning Application is a web-based application developed using Spring Boot and Vue.js, ThymeLeaf, Bootstrap for the frontend. This application provides an engaging platform to aid in learning Chinese. Users can input questions related to learning Chinese and get them answered by other users or experts. 

## Functionality

1. **User Registration & Login**: Users can create an account, log in, and manage their profiles.
2. **Questions & Answers**: Users can post questions about learning Chinese and also answer questions posted by other users.

## Technologies Used

- **Backend**: Spring Boot, Spring Security, Hibernate, and MySQL for database.
- **Frontend**: Vue.js, Thymeleaf, Bootstrap and Element UI for UI components.
- **Other**: Maven for project management, JUnit for testing, Axios for HTTP requests.

## Security

Spring Security is used for securing the web application. It handles user authentication and authorizes access to specific URLs based on user roles. It also provides session management and CSRF protection (though it's disabled in current configuration). Passwords are stored securely in the database using BCrypt hashing.

## Data Handling

Hibernate, which is a Java framework for Object-Relational Mapping (ORM), is used for data handling. It enables Java applications to interact with relational databases in an intuitive manner. The properties for Hibernate, such as the dialect, DDL auto, etc. are defined in the application properties file.

## Running the Application

Prerequisites:
- Java 8 or higher
- Maven
- MySQL Server

Follow these steps to run the application:

1. **Clone the repository**:
   ```
   git clone https://github.com/Beibaobao/ChineseLearningApp.git
   ```
   
2. **Set up MySQL Server**:
   Start your MySQL server. Create a new database called `chinese_learning` and update the `spring.datasource.username` and `spring.datasource.password` properties in `application.properties` file as per your MySQL configuration.
   
3. **Build the project**:
   Navigate to the project directory and run the following command:
   ```
   mvn clean install
   ```
   
4. **Run the application**:
   ```
   mvn spring-boot:run
   ```

You should now be able to access the application at `http://localhost:8080`.

## Testing

JUnit is used for unit testing in the application. To run the tests, use the following command:

```
mvn test
```

## Contributing
I would like to thank all the teachers,classmates and friends who helped me during this process. 
## License

This project is open-sourced under the [MIT license](LICENSE.md).

## Contact

If you have any questions, feel free to contact me.

.

