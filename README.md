# backendRun
Repositorio con el docker-compose y la estructura de carpetas

## Estructura

Para correr todos los microservicios y el backend en general usar la siguiente estructura de carpetas 

    some_folder/
    ├─ microservices/
    ├─ apigateway/
    ├─ reverseProxy/
    ├─ backendRun/
    │  ├─ docker-compose.yml

Despues de eso posicionarnos sobre la carpeta backendRun y usar el comando

    docker compose up 
