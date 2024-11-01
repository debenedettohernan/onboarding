FROM openjdk:21

# Establece el directorio de trabajo en el contenedor
WORKDIR /app/ms-personas

# Copia el archivo JAR a la imagen del contenedor
COPY target/*.jar /app/ms-personas/ms-personas.jar

ENTRYPOINT ["sh", "-c", "sleep 45 && java -jar /app/ms-personas/ms-personas.jar"]
#CMD ["java", "-jar", "ms-personas.jar"]
