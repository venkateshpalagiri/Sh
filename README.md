# CloudGateway
## URL
### Server.Port: http://localhost:9090/
### Eureka: http://localhost:9090/
### Swagger/OpenAPI: http://localhost:9090/swagger-ui/index.html
### Zipkin: http://localhost:9411/zipkin/

# ServiceRegistry
## URL:
### Server.Port: http://localhost:8761/
### Eureka: http://localhost:8761/
### Swagger/OpenAPI: http://localhost:8761/swagger-ui/index.html
### Zipkin: http://localhost:9411/zipkin/   //<!-- docker run -d -p 9411:9411 openzipkin/zipkin -->
<!-- docker start CONTAINER-ID // docker stop CONTAINER-ID -->

# ConfigServer
## URL:
### Server.Port: http://localhost:9296/
### Eureka: http://localhost:8761/
### Swagger/OpenAPI: http://localhost:9296/swagger-ui/index.html
### Zipkin: http://localhost:9411/zipkin/   <!-- docker run -d -p 9411:9411 openzipkin/zipkin -->
<!-- docker start CONTAINER-ID // docker stop CONTAINER-ID -->

# ProductService
## URL:
### Server.Port: http://localhost:8080/
### Eureka: http://localhost:8761/
### Swagger/OpenAPI: http://localhost:8080/swagger-ui/index.html
### Zipkin: http://localhost:9411/zipkin/   <!-- docker run -d -p 9411:9411 openzipkin/zipkin -->
<!-- docker start CONTAINER-ID // docker stop CONTAINER-ID -->

# PaymentService
## URL:
### Server.Port: http://localhost:8081/
### Eureka: http://localhost:8761/
### Swagger/OpenAPI: http://localhost:8081/swagger-ui/index.html
### Zipkin: http://localhost:9411/zipkin/   <!-- docker run -d -p 9411:9411 openzipkin/zipkin -->
<!-- docker start CONTAINER-ID // docker stop CONTAINER-ID -->

# OrderService
## URL:
### Server.Port: http://localhost:8082/
### Eureka: http://localhost:8761/
### Swagger/OpenAPI: http://localhost:8082/swagger-ui/index.html
### Zipkin: http://localhost:9411/zipkin/   <!-- docker run -d -p 9411:9411 openzipkin/zipkin -->
<!-- docker start CONTAINER-ID // docker stop CONTAINER-ID -->
