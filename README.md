<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>

[circleci-image]: https://img.shields.io/circleci/build/github/nestjs/nest/master?token=abc123def456
[circleci-url]: https://circleci.com/gh/nestjs/nest

#Ejecutar en desarrollo

1. clonar el repositorio
2. Ejecutar

```
 pnpm install
```

3. tener Nest CLI instalado

```
pnpm i -g @nestjs/cli
```

4. levantar la base de datos

```
docker-compose up -d
```

5. reconstruir la bd con el seed

```
http://localhost:3000/api/v2/seed
```
