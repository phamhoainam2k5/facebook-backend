# Facebook clone full stack

This project is a demo project to demonstrate how to implement basic operations of the `User` entity.

## Is there anything inside??

This project is based on the [Spring Boot](http://projects.spring.io/spring-boot/) project and uses the following packages to handle the BE part:
- Maven
- Spring Web
- Spring Data JPA
- MySQL
- JDBC API
- Lombok

To process and build the user interface we use ReactJS.

## Database configuration 
Create a MySQL database with the name `facebookclonedb` and add the credentials to `/resources/application.properties`.  
The default ones are :

```
spring.datasource.url=jdbc:mysql://localhost:3306/facebookclonedb
spring.datasource.username=root
spring.datasource.password=
spring.jpa.hibernate.ddl-auto=update
```

## Installation and Run
Because this is a project implemented using [Spring Boot](http://projects.spring.io/spring-boot/) technology with ReactJS, when cloned successfully, you need to do the following:
- Go to the `facebook-fontend` file and open the terminal to execute the `npm install` command.
- Once done, you can use the command `npm run dev` to run the program with the path [http://localhost:3000](http://localhost:3000).
- The file `facebook-backend` is the Spring boot project because it was created with Maven so you just need to import it into your IDE and launch the project.





