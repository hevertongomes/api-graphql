# API BLOG

## Como usar

Clonar no repositório: <https://github.com/hevertongomes/api-graphql>

Como alternativa para o mongo pode executá-lo usando o docker, mostrado a seguir

```bash
$ git pull mongo
$ docker run --name mongodb -p 27017:27017  -e AUTH=no mongo

## Para rodar o projeto.

$ cd api-graphql
$ yarn install
$ yarn dev
```

## Sobre o projeto

Projeto criado com base na playlist <https://www.youtube.com/playlist?list=PLPXWI3llyMiK9uw7tfljM2hnQl2qu6CeT> Para fins de estudo.
Projeto é a criação de uma api utilizando Apollo e Graphql e como bancode de dados é utilizado mondodb
