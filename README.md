# Products-ms

<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="120" alt="Nest Logo" /></a>
</p>

  <p align="center">A Products microservice built using Nest.js.</p>
    <p align="center">

## Project setup

### Dev

1. Clonar el repositorio
2. Instalar las dependencias
3. Crear un archivo `.env` en el root del proyecto basado en el archivo `.env.template`
4. Levantar el servidor de NATS

```
docker run -d --name nats-main -p 4222:4222 -p 6222:6222 -p 8222:8222 nats
```

5. Execute `npx prisma migrate dev` to create the database
6. Execute `npm run start:dev` to start the server
