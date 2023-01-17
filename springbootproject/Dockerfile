FROM openjdk
COPY ./target/maven-wrapper*.jar /usr/app/maven-wrapper.jar
WORKDIR /usr/app
EXPOSE 8084
ENTRYPOINT ["java","-jar","dockerDemo.jar"]
