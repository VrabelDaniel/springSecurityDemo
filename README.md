# Spring Security Demo

### Description
This is a simple Spring Boot application that demonstrates the use of Spring Security with JWT authentication and role-based access control.

### Guides
https://medium.com/@tericcabrel/implement-jwt-authentication-in-a-spring-boot-3-application-5839e4fd8fac

https://blog.tericcabrel.com/role-base-access-control-spring-boot/

### Docker command for MySQL
```shell
docker run -d -e MYSQL_ROOT_PASSWORD=secret -e MYSQL_DATABASE=taskdb --name mysqldb -p 3307:3306 mysql:8.0
```