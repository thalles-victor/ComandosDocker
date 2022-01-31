# ComandosDocker
Esses são os comandos que eu mais uso no docker, deixo eles aqui para ficar mais fácil a busca.

Cirando um novo container
```console
  sudo docker run --name <nome do container> -e POSTGRES_PASSWORD=<senha do container> -d -p <porta ex: 5432>:<porta ex: 5432> <tipo do container ex: postgres or mysql>
```
Verificando todos os conteiners intalado

```console
  sudo docker ps -a
```

Startando o container
```console
  sudo docker start <id do container>
```

Parando algum container
```console
  sudo docker stop <id do container>
```

Deletando o contianer 
```console
  sudo docker rm <id do container>
```
