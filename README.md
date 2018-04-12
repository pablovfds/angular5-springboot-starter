## A Spring boot, maven and Angular 5 starter Application

This is a multi-module Spring Boot Angular Maven starter app.

This project provides productive setup for building Spring Boot Angular applications. The application is divided into two Maven modules:

1. `backend`: This contains Java code of the application.
2. `frontend`: This contains source code for the Angular based frontend.

## Running the full application

You can build the package as a single artifact by running the `./mvnw clean install`.
Next, you can run the application by executing:

```bash
$ java -jar backend/target/backend-0.0.1-SNAPSHOT.jar 
```

The application will be accessible at `http://localhost:8080`. 
