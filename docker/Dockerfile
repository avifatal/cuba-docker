### Dockerfile

FROM openjdk:8
COPY . /usr/src/cuba
CMD apt-get update \
    apt-get install mysql-client \
    java  -jar /usr/src/cuba/app.jar 

