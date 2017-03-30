This project is a simple user management application. This applications is being secured using Spring Security4 validation, inegration MYsql database using hibernate. Remember-me functionality is also provided using TokenRepository. Here we are persisting the token in Mysql Db using persistentTokenRepository and hibernate. We are using Spring Jpa transaction. Every configurations are annotation driven. We have used JNDI for fetching datasource.

In pom.xml we have used Spring-boot for importing all spring dependency jars.

1. spring-boot-starter-data-jpa for Spring JPA Hibernate dependency.
2. spring-boot-starter-security for using Spring Security
3. spring-boot-starter-web for Spring MVC
4. spring-security-taglibs
