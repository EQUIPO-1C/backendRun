# backendRun
Repositorio con el docker-compose y la estructura de carpetas

## Estructura

Para correr todos los microservicios y el backend en general usar la siguiente estructura de carpetas 

    some_folder/
    ├─ microservices/
    ├─ apigateway/
    ├─ reverseProxy/
    ├─ interface/
    ├─ backendRun/
    │  ├─ docker-compose.yml

Correr el siguiente comando

    docker compose up -d 
