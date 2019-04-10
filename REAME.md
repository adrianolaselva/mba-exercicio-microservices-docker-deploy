

## Exemplo aplicação python rodando em container


#### Construir container

```sh
docker build --tag=fiaphello .
```
#### Rodar na porta 4000

```sh
docker run -p 4000:80 fiaphello
```
