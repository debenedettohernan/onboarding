FROM openjdk:21

# Establece el directorio de trabajo en el contenedor
WORKDIR /app/ms-cuentas

# Copia el archivo JAR a la imagen del contenedor
COPY target/*.jar /app/ms-cuentas/ms-cuentas.jar

ENTRYPOINT ["sh", "-c", "sleep 45 && java -jar /app/ms-cuentas/ms-cuentas.jar"]
#CMD ["java", "-jar", "ms-cuentas.jar"]
