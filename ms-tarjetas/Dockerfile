FROM openjdk:21

# Establece el directorio de trabajo en el contenedor
WORKDIR /app/ms-tarjetas

# Copia el archivo JAR a la imagen del contenedor
COPY target/*.jar /app/ms-tarjetas/ms-tarjetas.jar

ENTRYPOINT ["sh", "-c", "sleep 45 && java -jar /app/ms-tarjetas/ms-tarjetas.jar"]
#CMD ["java", "-jar", "ms-tarjetas.jar"]
