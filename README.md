# ComandosDocker
Esses são os comandos que eu mais uso no docker, deixo eles aqui para ficar mais fácil a busca.

Antes de criar um novo é bom verificar se a porta está em uso com o comando
```console
  sudo lsof -nP -iTCP -sTCP:LISTEN
```

Cirando um novo container
```console
  sudo docker run --name <nome do container> -e POSTGRES_PASSWORD=<senha do container> -d -p <porta ex: 5432>:<porta ex: 5432> <tipo do container ex: postgres or mysql>
```
Verificando todos os containers instalado

```console
  sudo docker ps -a
```

Estartando o container
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
