* Podemos criar um serviço com um número maior de réplicas: docker service create --name --replicas
* Desta maneira uma task será emitida, replicando este serviço nos Workers;
* Agora iniciamos de fato a orquestração;
* Podemos checar o status com: docker service ls