SpringBootOrderApp

A simple Spring Boot application to manage and view orders using RESTful APIs with JPA. This application demonstrates the basic CRUD functionality with a focus on the GET operation to retrieve all orders.

Features:-
* View all orders via a RESTful GET API.
* Use H2 in-memory database for lightweight persistence.
* Pre-loaded data for testing.
* Package structure follows com.klef.jfsd.exam.

Technologies Used:-
* Java 17 (or any supported Java version)
* Spring Boot (Web and JPA)
* H2 Database
* Maven (for project management)

Setup Instructions:-

* Clone the Repository:-
Copy code
git clone https://github.com/yourusername/SpringBootOrderApp.git
cd SpringBootOrderApp

* Build the Application:-
Ensure you have Maven installed:
mvn clean install

* Run the Application:-
 Start the Spring Boot application:
 mvn spring-boot:run

* Access the API:-
View all orders:
GET http://localhost:8080/api/orders
