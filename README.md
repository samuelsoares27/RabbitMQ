# RabbitMQ
Application using rabbitmq with api and consumer, conection with sql server using entity with layered architecture
Atention project with .net 6 and sql server, look the appsettings.json and change your connection string 

I'm using rabbitMQ with Docker

You can download docker and this image -> https://hub.docker.com/_/rabbitmq
but i choose this version using prompt to download -> docker pull rabbitmq:3.11.11-management 

after i can check using docker image ls and run this image -> docker run -d --hostname rabbit --name rabbit-server -p 15672:15672 -p 5672:5672 rabbitmq:3.11.11-management 

To create migration -> add-migration first-migration
and to finish create the database ->  update-database
Run both project Api and Consumer
It's easy to learn!!
