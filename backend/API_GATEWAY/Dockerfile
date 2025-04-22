FROM openjdk:17
EXPOSE 8093
ADD "target/API_GATEWAY-0.0.1-SNAPSHOT.jar" "APIMSP-docker.jar"
ENTRYPOINT ["java", "-jar", "APIMSP-docker.jar"]