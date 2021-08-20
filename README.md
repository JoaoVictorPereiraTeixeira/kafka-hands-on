# Tech talk - Kafka hands-on

## Running

### Passo 1
1) Via terminar entrar na pasta terminalkafka
2) Rodar os comandos:
```
docker-compose up -d
```
```
docker exec -it terminalkafka_kafka_1 bash
```
```
kafka-topics
```

Caso apareça uma lista de comandos disponíveis o passo 1 está concluído :)

### Passo 2
1) Ainda na pasta terminalkafka rodar o comando:
```
docker-compose down
```
2) Via terminar entrar na pasta gokafka
3) Rodar os comandos
```
docker-compose up -d
```
```
docker exec -it gokafka bash
```
```
go run producer/main.go
```

Caso apareça a mensagem Hello Kafka! o passo 2 está concluído ;)



