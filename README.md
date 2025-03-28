[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=BobApp-Back&metric=alert_status)](https://sonarcloud.io/summary/new_code?id=BobApp-Back)
[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=BobApp-Front&metric=alert_status)](https://sonarcloud.io/summary/new_code?id=BobApp-Front)

# BobApp

## Install

Clone project:

> git clone XXXXX

### Front-end 

Go inside folder the front folder:

> cd front

Install dependencies:

> npm install

Launch Front-end:

> npm run start;

#### Docker

Build the container:

> docker build -t bobapp-front .  

Start the container:

> docker run -p 8080:8080 --name bobapp-front -d bobapp-front

### Back-end

Go inside folder the back folder:

> cd back

Install dependencies:

> mvn clean install

Launch Back-end:

>  mvn spring-boot:run

Launch the tests:

> mvn clean install

#### Docker

Build the container:

> docker build -t bobapp-back .  

Start the container:

> docker run -p 8080:8080 --name bobapp-back -d bobapp-back

## SonarQube

https://sonarcloud.io/organizations/tom-devweb/projects
