* As imagens do Docker são divididas em camadas (layers);
* Cada instrução no Dockerfile representa uma layer;
* Quando algo é atualizado apenas as layers depois da linha atualizada são refeitas;
* O resto permanece em cache, tornando o build mais rápido;