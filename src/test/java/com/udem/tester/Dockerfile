FROM openjdk:11-ea-19-jre-slim
EXPOSE 8080
ADD target/tester.jar tester.jar
ENTRYPOINT ["java","-jar","/tester.jar"]

