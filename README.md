# Desenvolva um aplicativo Go com Docker Compose

desenvolvendo api com docker-compose e [air](https://github.com/cosmtrek/air) com hot reload
[link](https://firehydrant.io/blog/develop-a-go-app-with-docker-compose/) do tutorial

build o projeto

```
$ docker build -t go-and-compose .
```

rodando o projeto
```
$ docker run -e API_SERVER_ADDR=:3000 go-and-compose
```
obs: não se esqueça de subir o banco de dados
