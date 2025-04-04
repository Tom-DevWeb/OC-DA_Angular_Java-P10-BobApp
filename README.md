![GitHub Actions](https://img.shields.io/badge/github%20actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white)
![SonarQube](https://img.shields.io/badge/SonarQube-black?style=for-the-badge&logo=sonarqube&logoColor=4E9BCD)
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)

# 🃏 BobApp

## 🔎 SonarQube
_https://sonarcloud.io/organizations/tom-devweb/projects_

### Front

[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=BobApp-Front&metric=alert_status)](https://sonarcloud.io/summary/new_code?id=BobApp-Front)
[![Bugs](https://sonarcloud.io/api/project_badges/measure?project=BobApp-Front&metric=bugs)](https://sonarcloud.io/summary/new_code?id=BobApp-Front)
[![Bugs](https://sonarcloud.io/api/project_badges/measure?project=BobApp-Front&metric=bugs)](https://sonarcloud.io/summary/new_code?id=BobApp-Front)
[![Coverage](https://sonarcloud.io/api/project_badges/measure?project=BobApp-Front&metric=coverage)](https://sonarcloud.io/summary/new_code?id=BobApp-Front)
[![Duplicated Lines (%)](https://sonarcloud.io/api/project_badges/measure?project=BobApp-Front&metric=duplicated_lines_density)](https://sonarcloud.io/summary/new_code?id=BobApp-Front)
### Back

[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=BobApp-Back&metric=alert_status)](https://sonarcloud.io/summary/new_code?id=BobApp-Back)
[![Bugs](https://sonarcloud.io/api/project_badges/measure?project=BobApp-Back&metric=bugs)](https://sonarcloud.io/summary/new_code?id=BobApp-Back)
[![Code Smells](https://sonarcloud.io/api/project_badges/measure?project=BobApp-Back&metric=code_smells)](https://sonarcloud.io/summary/new_code?id=BobApp-Back)
[![Coverage](https://sonarcloud.io/api/project_badges/measure?project=BobApp-Back&metric=coverage)](https://sonarcloud.io/summary/new_code?id=BobApp-Back)
[![Duplicated Lines (%)](https://sonarcloud.io/api/project_badges/measure?project=BobApp-Back&metric=duplicated_lines_density)](https://sonarcloud.io/summary/new_code?id=BobApp-Back)

## 🐳 DockerHub

_https://hub.docker.com/repositories/tomwebdev_

## 🛠️ Install

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

