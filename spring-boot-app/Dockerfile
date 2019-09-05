# create image from base image openjdk which a linux and has Java
FROM openjdk:8-jre-alpine
# copy WAR into image
COPY target/spring-boot-app-0.0.2-SNAPSHOT.war /app.war 
EXPOSE 8081
# run application with this command line 
CMD ["/usr/bin/java", "-jar", "-Dspring.profiles.active=default", "/app.war"]
