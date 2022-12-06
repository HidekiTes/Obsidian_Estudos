* A conexão entre instâncias usa um driver diferente, o overlay;
* Podemos criar primeiramente a rede com docker network create;
* E depois ao criar um service adicionar a flag --network para inserir as instâncias na nossa nova rede;