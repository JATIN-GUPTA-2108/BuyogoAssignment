
### Description ###

This is a simple project for  registry for Govt funded Training Centers which is developed using simple Rest APIs. This application performs all CRUD operations.

### Installation ###
For installing this application firstly i opened spring.io then here give all details of project which are needed.
Then i added all dependencies like h2 database, Spring web, springDataJPA etc.
Then after downloading the zip folder extract this folder and import into STS.

### Accessing the application: ###
 
 For Getting all items use
 
 GET: localhost:8080/api/training-centers
 
 Post:localhost:8080/api/training-centers (if the data is not proper then it will also show validation messages.)
 
 Update:localhost:8080/api/training-centers/{id} (if id does not found then it will return exception like Training center not found with id: " + id)
 And it will also show validation messages .
 
 GetbyId:localhost:8080/api/training-centers/{1id} (if id does not found then it will return exception like Training center not found with id: " + id)
 
 Delete:localhost:8080/api/training-centers/{id} (if id does not found then it will return exception like Training center not found with id: " + id)
 
 ### Technology Stack ###

- Spring Boot 
- Spring Data JPA
- Database – H2Database
- JDK 11







