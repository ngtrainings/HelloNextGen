# HelloNextGen

- build_simple_java
```
Click on https://www.katacoda.com/courses/docker/deploying-first-container
docker run -p 80:8080 -p 50001:50000 -v jenkins_home:/var/jenkins_home jenkins/jenkins:lts-jdk11

or 

https://learning.oreilly.com/scenarios/jenkins-sandbox/9781098117825/

Configure Maven version
Jenkins install Maven for you
    You must go to Jenkins Global Tool Configuration, and configure a Maven version with automatic installer (from the web).
    In Job configuration, for Maven Version, you must select that particular version that you've just configured.

Create new build_simple_java pipeline https://github.com/ngtrainings/HelloNextGen.git
Submit new build
Go to terminal and run jar file
cd /var/jenkins_home/workspace/jenkin-docker-integration/target/
java -jar HelloNextGen-0.0.1-SNAPSHOT.jar
```

- build_simple_java_git_upload
```
Create new build_simple_java_docker_upload pipeline https://github.com/ngtrainings/HelloNextGen.git
Configure git hub credentials
Submit new build
Verify jar file in git hub
download and run in katakoda
git clone https://github.com/ngtrainings/HelloNextGen.git
java -jar jar file name
```

- build_multi_branch_pipeline
```
Create new build_multi_branch_pipeline pipeline https://github.com/ngtrainings/HelloNextGen.git
Submit new build iwth params
Verify pipeline
```
