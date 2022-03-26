# docker

> O docker-compose identifica os containers na raiz do projeto (juntamente com o `docker-compose.yml`)

## subir ambiente

```sh
docker-compose up -d
```

> Caso precise rebuildar a imagem (modificações no `Dockerfile`) utilize docker-compose up -d --build

## descer ambiente

```sh
docker-compose down
```

## status

```sh
docker-compose ps
```