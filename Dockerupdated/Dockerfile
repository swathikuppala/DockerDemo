FROM openjdk:8
ADD target/maven-jar-plugin-1.0-SNAPSHOT.jar /maven-jar-plugin-1.0-SNAPSHOT.jar 
ENTRYPOINT ["java", "-jar","maven-jar-plugin-1.0-SNAPSHOT.jar"]
EXPOSE 8080