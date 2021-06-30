FROM openjdk:16
COPY ./target/tax-0.0.1-SNAPSHOT.jar /usr/app/
WORKDIR ./usr/app/
EXPOSE 8080
ENTRYPOINT ["java", "-jar", "tax-0.0.1-SNAPSHOT.jar"]