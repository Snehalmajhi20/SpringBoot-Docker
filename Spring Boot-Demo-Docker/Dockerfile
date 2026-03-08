FROM eclipse-temurin:17

LABEL maintainer="snehalmajhi123@gmail.com"
WORKDIR /app
COPY target/Docker-0.0.1-SNAPSHOT.jar /app/springboot-demo-docker.jar
ENTRYPOINT ["java","-jar","springboot-demo-docker.jar"]