* Para criar um serviço e expor nossos Pods devemos utilizar o comando: kubectl expose deployment --type=--port=
* Colocaremos o nome do Deployment já criado;  
* O tipo de Service, há vários para utilizarmos, porém o Load Balancer é o mais comum, onde todos os Pods são expostos;
* E uma porta para o serviço ser consumido;