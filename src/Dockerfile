FROM openjdk:8

EXPOSE 8080

ADD /var/jenkins_home/workspace/test/target/HelloNextGen-0.0.1-SNAPSHOT.jar HelloNextGen-0.0.1-SNAPSHOT.jar

ENTRYPOINT ["java","-jar","HelloNextGen-0.0.1-SNAPSHOT.jar"]
