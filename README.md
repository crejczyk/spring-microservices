[![Build Status](https://api.travis-ci.org/crejczyk/spring-microservices.svg?branch=master)](https://travis-ci.org/crejczyk/spring-microservices)
[![Coverage Status](https://coveralls.io/repos/github/crejczyk/spring-microservices/badge.svg)](https://coveralls.io/github/crejczyk/spring-microservices)
[![GitHub license](https://img.shields.io/github/license/mashape/apistatus.svg)](https://github.com/sqshq/PiggyMetrics/blob/master/LICENCE)
[![Quality Gate](https://sonarcloud.io/api/project_badges/measure?project=com.softmill%3Asoftmill&metric=alert_status)](https://sonarcloud.io/dashboard/index/com.softmill%3Asoftmill)

# Spring microservices POC


## Run HTML code coverage report
- `mvn clean verify -Pjacoco`


## Run MONGO-ACCOUNT on Docker
- `docker run -e MONGODB_PASSWORD='MONGODB_PASSWORD' -e INIT_DUMP='account-service-dump.js' -p 27017:27017 mongo-user:latest`


## Run RabbitMQ on Docker
- `docker run -d --hostname my-rabbit --name some-rabbit -p 15672:15672 -p 5672:5672 rabbitmq:3-management`

## Hystrix Dashboard
- `http://localhost:8080/hystrix/`