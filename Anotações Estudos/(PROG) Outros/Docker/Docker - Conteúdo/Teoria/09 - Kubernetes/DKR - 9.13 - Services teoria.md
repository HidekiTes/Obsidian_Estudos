* As aplicações do Kubernetes não tem conexão como mundo externo;
* Por isso precisamos criar um Service, que é o que possibilita exporos Pods;
* Isso acontece pois os Pods são criados para serem destruídos e perderem tudo, ou seja, os dados gerados neles também são apagados;
* Então o Service é uma entidade separada dos Pods, que expõe eles a uma rede;