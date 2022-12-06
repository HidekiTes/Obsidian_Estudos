* Bind mount também é um volume, porém ele fica em um diretório que nós especificamos;
* Então não criamos um volume em sim, apontamos um diretório;
* O comando para criar um bind mount é: docker run /dir/data:/data
* Desta maneira o diretório /dir/data no nosso computador, será o volume deste container;