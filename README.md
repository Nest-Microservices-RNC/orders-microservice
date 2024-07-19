# Orders MicroService

## Development steps

1. Clonar proyecto
2. Crear archivo `.env` basado en el archivo `.env.template`
3. Levantar la base de datos con `docker-compose up -d`
4. Levantar el servidor de NATS
```
docker run -d --name nats-server -p 4222:4222 -p 6222:6222 -p 8222:8222 nats
```
5. Levantar el proyecto con `npm run start:dev`