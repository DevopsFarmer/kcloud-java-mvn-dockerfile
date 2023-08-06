# Dockerize a Maven Java project 
Steps
```
mvn install
docker build -t java-mvn-dockerfile:v1 .
# docker tag java-mvn-dockerfile:v1 <dockerhub-repo-name>/<tag>
# docker login
# docker push <dockerhub-repo-name>/<tag>
```
