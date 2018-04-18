# Curso de docker Avancado

Este repositorio contem projeto de exemplo usado no curso de docker avancado

## Configurando Ambiente

### a) Instalar o Docker:

Referencia: [Documentacao oficial](https://docs.docker.com/install/#supported-platforms)

Usuario Linux Debian/Ubunto

```
$ curl -fsSL get.docker.com -o get-docker.sh

$ sudo sh get-docker.sh
```

### b) instalar o Docker Compose:

Referencia: [Documentacao Oficial](https://docs.docker.com/compose/install/#install-compose)

```
$ sudo curl -L https://github.com/docker/compose/releases/download/1.19.0/docker-compose-`uname -s-uname -m`-o /usr/local/bin/docker-compose

$ sudo chmod +x /usr/local/bin/docker-compose
```

## Rodando Projeto

* Acesse a pasta de cada projeto

* Contrua os conteineres docker

Dentro da pasta de cada projeto, execute docker-compose para construi os conteineres do software

```
$ docker-compose up -d
```

Lendo o logs
```
$ docker-compose logs -f
```

Listando os containers em execucao
```
$ docker-compose ps
```

Stopando os containers
````
$ docker-compose down
```
