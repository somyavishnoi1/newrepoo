FROM openjdk
COPY ./target/demo-docker*.jar /usr/app/dockerDemo.jar
WORKDIR /usr/app
EXPOSE 8084
ENTRYPOINT ["java","-jar","dockerDemo.jar"]
