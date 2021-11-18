# springboot-application-4SAE8
### Spring boot project - class 4SAE8


( Client Controller + Stock Controller + Swagger + Lombok ...etc) 

- MVC REST - Swagger ( 11 November 2021)
- Test Unitaires + Lombok 
- Spring Data JPA JPQL (31 october 2021)
- Crud Repository (27 october 2021) 
- Spring Data JPA : Associations (20 october 2021) 
- Spring Data JPA ( 13 october 2021)




### changes : 

file : C:\Users\medaminebt\Downloads\project-spring-boot\project-spring-boot\src\main\resources\application.properties


create empty file : 


C:/Users/medaminebt/Downloads/project-spring-boot/project-spring-boot/spring_logs/spring_log_file.log







```

### DATABASE ###
#spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver
spring.datasource.url=jdbc:mysql://localhost:3306/springDB
spring.datasource.username=root
spring.datasource.password=


### Logs ###
logging.level.root=INFO
logging.file.name=C:/Users/medaminebt/Downloads/project-spring-boot/project-spring-boot/spring_logs/spring_log_file.log
logging.pattern.console=%d{yyyy-MM-dd HH:mm:ss} - %-5level - %logger{60} - %msg%n
logging.logback.rollingpolicy.max-file-size=100KB  

```






Create DB on wampp server phpmyadmin ( data base name :  springdb ) 


SS of DB    http://localhost/phpmyadmin : 
![SS of DB http://localhost/phpmyadmin ](https://i.imgur.com/fJt96cd.png)










Generate getters & setters for : client.java , stock.java , facture.java ...etc 




### TEST on postman : 

GET :  
http://localhost:8080/api/clients/
