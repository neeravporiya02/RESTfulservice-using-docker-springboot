# RESTfulservice-using-docker-springboot
This repository is on RESTful service using Docker and Spring Boot. For the front end I have used HTML, Jquery and Ajax to display data from Json.
This repository has two folders one which has the HTML file in it and the other with Spring Boot API file.

## Steps to follow
1. Unzip the file.
2. First build the docker file by using command
### `docker build -t springio/gs-spring-boot-docker .` (It can be anyname after -t)
3. Then run the docker file by using the command
### `docker run -p 8081:8081 springio/gs-spring-boot-docker` ( the name that you gave after -t)

So with this the docker file is up and running

Now just open the service.html file and the code should be running as expected.


