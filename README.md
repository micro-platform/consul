# Consul Docker for micro-platform application with Spring Cloud.

A docker-compose using the official **consul** image.

## How to use it ?

Simply run `docker-compose up -d` and go to `http://localhost:8500`to display the UI interface of consul.

## Add configuration

For the moment, all .yml files are stored in `/config` directory. The naming convention is really easy to follow : `application-{MICROSERVICES-NAME}.yml`.
