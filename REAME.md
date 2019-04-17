

## Exemplo aplicação python rodando em container


#### Construir container

```sh
docker build --tag=fiaphello .
```
#### Rodar na porta 4000

```sh
docker run -p 4000:80 fiaphello
```

### Baixar imagem do dockerhub

```sh
docker pull adrianolaselva/app-1-fiap-microservico:0.1.0
```

### Subir container como serviço


```sh
docker stack deploy --compose-file docker-compose.yml microservice
```

### Aumentar número de instâncias para 5

```sh
docker service scale microservice_app=5
```
s
