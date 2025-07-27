# configserver

Todo with rabit mq

# latest RabbitMQ 4.x - run this docker commands
docker run -it --rm --name rabbitmq -p 5672:5672 -p 15672:15672 rabbitmq:4-management

#add dependency in all services
<!-- https://mvnrepository.com/artifact/org.springframework.cloud/spring-cloud-starter-bus-amqp -->
<dependency>
    <groupId>org.springframework.cloud</groupId>
    <artifactId>spring-cloud-starter-bus-amqp</artifactId>
    <version>4.2.1</version>
</dependency>


# add in all services 
spring
rabbitmq:
host:"localhost"
port:5692
username:"guest"
password:"guest""


#loans service invol=ke /busrefresh  endpoint then in all services configs will be reflected


#if this trigger automacticaly create git hub webhooks

add dependecny in mconfig serverf
<!-- https://mvnrepository.com/artifact/org.springframework.cloud/spring-cloud-config-monitor -->
<dependency>
    <groupId>org.springframework.cloud</groupId>
    <artifactId>spring-cloud-config-monitor</artifactId>
    <version>4.2.3</version>
    <scope>runtime</scope>
</dependency>

install this 
brew install hookdeck/hookdeck/hookdeck

run int terminal
->hookdeck login --cli-key 2ohqokvy625snsad7dfvzga31uny8y31ujwafpo7tyxgz5ufo0

->hookdeck listen 8071 Source
->/monitor
->localhost

paste the url webhooks 
conternt type is json
