* Podemos adicionar um novo serviço com o comando: docker swarmjoin--token :
* Desta forma duas máquinas estarão conectadas;
* Esta nova máquina entra na hierarquia como Worker;
* Todas as ações (Tasks) utilizadas na Manager, serão replicadas em Nodes que foram adicionados com join;