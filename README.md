# microservice-nestjs-rabbitmq

![alt text](https://res.cloudinary.com/dxeuxy7ik/image/upload/MicroserviceRabbitmqCommunicationDarkMode_jpfyos)



## Installation

1. Clone the repository
--------------------------------------------------------------------------------

```bash
    git clone https://github.com/HectorMartinDama/microservice-nestjs-rabbitmq.git
```

2. Install dependencies the both 
--------------------------------------------------------------------------------

```bash
    cd microservice-nestjs-rabbitmq
    # Install dependencies of the api
    cd api
    npm install
    # Install dependencies of the microservice
    cd email-microservice
    npm install
```

3. Up the rabbitmq instancie (you need to have docker installed on your machine)
--------------------------------------------------------------------------------

```bash
    cd email-microservice
    docker-compose up -d
```

Go to the url http://localhost:15672 in your browser. The user and password of the image it's ```guest``` ```guest```.


## Commands

|  |  |
|-----------|-----------|
| Running the app development | ```npm run start``` |
| Runnig the app watch mode | ```npm run start:dev``` |
| Build the app | ```npm run build``` |
| Up the rabbitmq instancie | ```docker-compose up -d ``` |

## Documentation

[Create microservice with nestjs](https://docs.nestjs.com/microservices/basics)
[Documentation](https://linktodocumentation)
[Documentation](https://linktodocumentation)





