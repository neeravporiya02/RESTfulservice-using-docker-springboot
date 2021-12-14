# RESTfulservice-using-docker-springboot
This repository is on RESTful service using Docker and Spring Boot. For the front end I have used HTML, Jquery and Ajax to display data from Json.
This repository has two folders one which has the HTML file in it and the other with Spring Boot API file.

## About the application
So this is a Spring Boot application with a hardcode Json data (Customer.json) and it consists of 4 GET API menthods.

### The application end points used are
1. `/customers` : Gets us list of customers
2. `/customers/{id}` : Gets a particular user details
3. `/customers/{id}/orders` : Get orders for particular user.
4. `/customers/{id}/orders/{id}` : Here we fetch one particular order of a particular user.

We then create a Docker file and build and run it to create a Docker Container which will fetch us the above data.

Then we use a webpage (simple front end UI) to show the endpoints in action.

## Steps to follow
1. Unzip the file.
2. Go to root of that folder and then run that path in cmd 
3. once the cmd opens, then in that we write the command to build and run Docker container
4. First build the docker file by using command
### `docker build -t springio/gs-spring-boot-docker .` (It can be anyname after -t)
3. Then run the docker file by using the command
### `docker run -p 8081:8081 springio/gs-spring-boot-docker` ( the name that you gave after -t)

So with this the docker file is up and running

Now just open the service.html file and the code should be running as expected.


