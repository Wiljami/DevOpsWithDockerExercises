FROM openjdk:8-jdk-alpine
COPY . .
RUN ./mvnw package
CMD ["java", "-jar", "./target/docker-example-1.1.3.jar"]
EXPOSE 8080
