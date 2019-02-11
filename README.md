## Service-Discovery (Netflix OSS Eureka)

####
Build the service and run it
* Build using maven
```
mvn clean install
```
* Run the jar
    - App will be launched on **8081** port you can change it as per your need.
```
java -jar eureka-server-demo-0.0.1-SNAPSHOT.jar --server.port=8081
```

* Test the content using your favourite browser and call the below rest endpoint
```
http://localhost:8081
```
