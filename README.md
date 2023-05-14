# eureka-server
Server to discover microservices

- Connect to http://localhost:8761/
  Here, you can see the metadataa about all the services and instances running.
  
  ![eureka2](https://github.com/jadhavpooja2121/eureka-server/assets/31277282/4fd32083-d163-4577-9422-a14b49e457d6)

## Steps
- Run the Eureka server project as Spring boot app
- Run a service
- To run a service instance on a different port follow the below steps
 - You need to have server.port property in application.json with different other port than 8080
 - Also check version compatibility for Spring cloud, Java, Spring 
 - MVN clean -> MVN install -> MVN build, this will create a build 
 - Use `java -jar target/actjhello-0.0.1-SNAPSHOT.jar -Dserver.port=8789`
 
