# Articles Forum (Spring MVC)

Web application where authors publish articles and readers browse them. Built with classic Spring MVC (no Spring Boot) and deployed as a WAR to Tomcat.

## Features

- Registration, login and password reset pages
- Spring Security authorization
- Article CRUD
- Author pages
- Hibernate persistence in PostgreSQL

## Tech stack

Java, Spring MVC, Spring Security, Hibernate, Thymeleaf, Bootstrap, PostgreSQL, Tomcat, Maven

## Getting started

Create the PostgreSQL database `forum`, set the credentials in `src/main/resources/hibernate.cfg.xml`, build with `mvn package` and deploy the WAR to Tomcat.
