# Hello go all

This project contains a simple hello world go program that will be used in Maratona Full Cycle 3 event.

## Generating build version

First, make sure you have the lastest golang version (> 1.11) installed on your machine and then run the following command:

```sh
$ go build -o hello-all .
```

It will generate a binary with we will use on container. The Dockerfile uses this binary to create a scrath container and defines it as entrypoint.

## docker image

To run this container, execute in your terminal:

```sh
$ docker pull lesilva00/hello-go-all
```

## Challenge description (portuguese)

O primeiro desafio dessa maratona consiste em criar um "Hello Full Cycle" utilizando a linguagem Golang.
Basicamente quando o arquivo compilado for executado, deverá ser exibido: Hello Full Cycle.
Se tudo estiver funcionando de forma adequada, gere uma imagem docker que quando executada deva rodar o programa criado em Golang.

Faça o push da imagem no Docker Hub e informe a url da imagem na área de entrega do desafio abaixo. 
