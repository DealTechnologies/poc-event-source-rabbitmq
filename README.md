# Introduction 
Prova de conceito utilizando mensageria com rabbitmq em background service

# Getting Started

> Pull rabbitmq official image on docker hub

- [On Docker](https://hub.docker.com/_/rabbitmqd)

> Create free mongo db cluster on cloud or official image on docker hub

- [On Free Cloud Official](https://www.mongodb.com/cloud/atlas)
- [On Free Cloud Third Party](https://mlab.com/)
- [On Docker](https://hub.docker.com/_/mongo)

> Set varables into solutions **../microservices.poc/*/**appsettings.json**
- MongoSettings : **<your_mongo_connection>**
- ConnectionStrings:DefaultConnection : **<your_sql_connection>**
- Open package management console and run : **update-database**
- Run sln : **dotnet run**

- Use rabbitmq dashboard:  **http://localhost:15672**

# Build 
run command: **dotnet build**

# More

- [Dotnet](https://dotnet.microsoft.com/download)
- [Background Service](https://docs.microsoft.com/pt-br/dotnet/architecture/microservices/multi-container-microservice-net-applications/background-tasks-with-ihostedservice)
- [Mongo DB](https://www.mongodb.com/)
- [EF.Core](https://docs.microsoft.com/pt-br/ef/core/managing-schemas/migrations/?tabs=dotnet-core-cli)
- [RabbitMQ](https://www.rabbitmq.com/#getstarted)
- [Docker](https://www.docker.com/)