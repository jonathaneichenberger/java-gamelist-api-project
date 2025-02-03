# Use a imagem oficial do OpenJDK com Java 21
FROM openjdk:21-jdk-slim

# Defina o diretório de trabalho no container
WORKDIR /app

# Copie o arquivo JAR da sua aplicação para o diretório de trabalho
COPY target/gamelist-0.0.1-SNAPSHOT.jar app.jar

# Exponha a porta em que a aplicação Spring Boot irá rodar
EXPOSE 8080

# Comando para rodar a aplicação Spring Boot
ENTRYPOINT ["java", "-jar", "app.jar"]
