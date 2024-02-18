FROM maven:3.8.4-jdk-8-slim

WORKDIR /app

COPY . .

RUN mvn clean package -DskipTests

CMD ["java", "-jar", "target/login-0.1.0.jar"]

EXPOSE 8000
