# Spring _tasks_ not boot app. 
## You could add, change or delete tasks.
### Java 17, tomcat 10, docker.

 To start in docker: run command `docker-compose up` and go to localhost:8080/root

 To star without docker, change application.properties `spring.datasource.url=jdbc:mysql://db:3306/todo on to spring.datasource.url=jdbc:mysql://localhost:3306/todo` and start mySQL.
