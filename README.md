# elearning-plateform

## Requirements

For building and running the application you need:

- [Eclipse IDE for Enterprise Java and Web Developers](https://www.eclipse.org/downloads/packages/release/2021-06/r/eclipse-ide-enterprise-java-and-web-developers)
- [Visual Studio Code](https://code.visualstudio.com)
- [JDK 1.8](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)
- [Spring Tools 4 (aka Spring Tool Suite 4) 4.11.0.RELEASE](https://marketplace.eclipse.org/content/spring-tools-4-aka-spring-tool-suite-4)
- [Lombok](https://projectlombok.org/download)
- [MySQl](https://dev.mysql.com/downloads/installer/)
- [Node.js](https://nodejs.org/en/download/)
- [Angular 12](https://angular.io/guide/setup-local)

## Backend (Spring Boot)

There are several ways to run a Spring Boot application on your local machine. One way is to execute the `main` method in the `com.altran.elearningplateform.ElearningplateformApplication` class from your IDE.

Alternatively you can use the [Spring Boot Maven plugin](https://docs.spring.io/spring-boot/docs/current/reference/html/build-tool-plugins-maven-plugin.html) like so:

```shell
mvn spring-boot:run
```

### Open Api (Swagger)

Navigate to : http://localhost:8080/swagger-ui/index.html?configUrl=/v3/api-docs/swagger-config#/


## Frontend (Angular 12)

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 12.1.1.

### Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.
Run `json-server --watch db.json`. to load values of some components.

### Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

### Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

### Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

### Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

### Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
