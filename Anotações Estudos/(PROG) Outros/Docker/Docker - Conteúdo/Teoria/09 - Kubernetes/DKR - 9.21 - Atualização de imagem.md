* Para atualizar a imagem vamos precisar do nome do container, isso é dado na Dashboard dentro do Pod;
* E também a nova imagem deve ser uma outra versão da atual, precisamos subir uma nova tag no Hub;
* Depois utilizamos o comando: kubectl set image deployment/=