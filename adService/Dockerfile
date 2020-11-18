FROM openjdk:11
WORKDIR /Users/max_slob/git/AdService
COPY target/adService-0.0.1-SNAPSHOT.jar service.jar
EXPOSE 8083
CMD ["java", "-jar", "service.jar"]