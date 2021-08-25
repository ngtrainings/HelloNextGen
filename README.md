# HelloNextGen

- build_simple_java
```
Click on https://www.katacoda.com/courses/docker/deploying-first-container
docker run -p 80:8080 -p 50001:50000 -v jenkins_home:/var/jenkins_home jenkins/jenkins:lts-jdk11
Configure Maven version
Jenkins install Maven for you
    You must go to Jenkins Global Tool Configuration, and configure a Maven version with automatic installer (from the web).
    In Job configuration, for Maven Version, you must select that particular version that you've just configured.

Create new build_simple_java pipeline https://github.com/ngtrainings/HelloNextGen.git
Submit new build
```

- build_simple_java_git_upload
```
Create new build_simple_java_docker_upload pipeline https://github.com/ngtrainings/HelloNextGen.git
Configure docker hub credentials
Submit new build
Verify image in docker hub
run in katakoda
```
