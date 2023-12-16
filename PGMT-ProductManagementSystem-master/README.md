# PGMT-ProductManagementSystem

                                                       `Technical Documentation`

Product  Management System (PM -GT) is a web-based application that enables local supermarkets  to manage their operations and improve their services. The system will enable Supermarket owners to maintain their sales .

The PM -GTis built using the Model-View-Controller (MVC) architecture, which separates the application logic from the user interface and the data storage. The MVC architecture allows for modular development, easy maintenance, and scalability of the application.

The PM -GTuses the following technologies:

The front-end of the application is developed using HTML, CSS, and JavaScript. The front-end communicates with the back-end.

The back-end of the application is developed using Java and spring runtime environment that allows for asynchronous and event-driven programming. The back-end handles the business logic, authentication, authorization, and data validation of the application.

The database of the application is PostgreSQL database that stores data in flexible and schema-less documents. PostgreSQL allows for fast and efficient data retrieval and manipulation.

The PM -GT follows the agile methodology for software development, which involves iterative and incremental delivery of working software. The PM -GT uses GitHub as a version control system and a collaboration platform.



1.Architecture Overview:
The  Product Management System is developed as a web-based application using a three-tier architecture:
Presentation Layer: This layer handles the user interface and interacts with the users(supermarket cashiers). It is implemented using HTML, CSS, and JavaScript for the front-end. The fronted communicates with the back-end to fetch and update data.
Application Layer: This layer consists of the back-end logic and business rules of the system. It is implemented using Java and the Spring Boot framework. The application layer handles data processing, validation, and integration with the database.
Data Layer: This layer is responsible for managing the data persistence. It uses a relational database management system (RDBMS) to store and retrieve data. The database interactions are handled using an ORM (Object-Relational Mapping) framework such as Hibernate.
2.Implementation Details:
Programming Language: Java
Framework: Spring Boot
Web Technologies: HTML, CSS, JavaScript
Database: Relational Database Management System (RDBMS)
ORM Framework: Spring Data JPA
Build Tool: Maven
Version Control: Git

3.Back-end Implementation:

The back-end is implemented using Java and the Spring Boot framework, which provides a robust and scalable foundation for developing web applications.
The Spring Boot framework simplifies the development process by providing pre-configured components, such as dependency injection, MVC (Model-View-Controller) architecture.
Controllers: The application defines controllers that handle incoming requests from the front-end. These controllers process the requests, interact with the appropriate services, and return the response back to the front-end.
Services: The services contain the business logic of the application. They handle data processing, validation, and communicate with the data access layer.
Data Access Layer: The data access layer is responsible for interacting with the database. It uses an ORM framework like Spring Data JPA to map Java objects to database entities and perform CRUD (Create, Read, Update, Delete) operations.
Models: The models represent the data entities of the system. They define the structure of the objects stored in the database and are used for data validation and mapping.

4.Front-end Implementation:
5.
The front-end is implemented using HTML, CSS, and JavaScript.
HTML is used to structure the web pages and define the user interface elements.
CSS is used to style the web pages and create an appealing and intuitive user interface.
The front-end communicates with the back-end API using HTTP requests, typically in JSON format, to fetch data, send updates, and receive responses.
Database:
The system uses a relational database management system (RDBMS) to store and retrieve data.
The choice of specific RDBMS (PostgreSQL).
The database schema is designed to support the entities and relationships required by the application, such as products, buyproducts
Tables are created for each entity, and appropriate indexes and constraints are defined to ensure data integrity and performance.

6.Security:
The application implements security measures to protect sensitive data and ensure authorized access.
User authentication and authorization are implemented using industry-standard security practices, such as password hashing, session management, and role-based access control.
Secure communication over HTTPS (HTTP Secure) is enforced to protect data transmission between the frontend and backend.

7.Deployment:
The application can be deployed on a web server or cloud platform, Heroku.
Configuration files are used to specify application settings, such as database connection details, and other configurable parameters.
Monitoring and logging mechanisms can be implemented to track application performance, identify issues, and ensure system availability.
Libraries and Frameworks:
The Product Management System utilizes several libraries and frameworks to enhance development efficiency and provide additional functionality. Some of the notable ones include:
Spring Security: Used for implementing authentication and authorization features, ensuring secure access to the application.
Thymeleaf: A server-side Java template engine used for rendering dynamic content on the web pages.
Hibernate: An ORM framework used for mapping Java objects to relational database entities and performing database operations.
Postgres Connector (or other appropriate database drivers): Used to connect to the relational database and execute SQL queries.







                                             `User Documentation`

The Product Management System is a web-based application that enables low level supermarket owners to manage their operations and improve their services. 

To use the application, you need to follow these steps:

1. Visit the website https://kj-productmanagement.herokuapp.com/ and  upon request you you will be faced with a Login page.
2. Enter your username and password that you created. If you do not have an account, you can request one by clicking on the "Register" button and filling out the form with your details.
3. Once you are logged in, you will see a dashboard with various options to access different features of the application. You can use the menu on the left side of the screen to navigate between different sections, such as "Add Products", "List Products", "Buy Products ",” List Bought Products , for the admin.
4. To add a new product into stock, click on the "Add Products" section and then enter its details
5. To view or edit an existing Products in stock you need to be the admin by, clicking on the "List Products" section and then click on the icon update of the product you want to  edit. You can also delete a product by clicking on the "Delete" icon on that page.
6. To buy products, click on the "Buy products " section, You will be prompted to choose the product you want ,then enter quantity and then buy 
7. To View the sales of the day click on the “List Bought Products” and there will be detailed view of the sales on various days.
8. To generate reports by clicking on the "Reports" icons and then select a report type from the menu bar (PDF ). 



More detail explanation


Visit the website https://kj-productmanagement.herokuapp.com/ and click on the "Login" button on the top of the homepage.

Login Credentials
To access the application as an admin, please use the following login credentials:
Email: admin@gmail.com
Password: keronisadmin

User (supermarket cashier)

Email: test@gmail.com
Password: 12345678

For the rest you can register and login by following the prompts.

 Keep in mind the mobile number must be 10 numbers and above and the password must be strong with minimum 8 characters.

Generating Reports
The Reports section provides  reports  to gain insights into Product stock
1.Locate the Download list button  and click it  .
Note that it will be  "PDF" Format

Logout
To log out of the application, click on the "Logout" icon in the top navigation bar.

If you have any questions or issues while using the application, please contact at keronjunior234@gmail.com.

