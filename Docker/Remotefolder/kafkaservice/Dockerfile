FROM openjdk:18
WORKDIR /app
COPY ./kafkaservice.jar  /app
EXPOSE 8081
CMD [ "java","-Dspring.profiles.active=uat","-jar","kafkaservice.jar" ]
