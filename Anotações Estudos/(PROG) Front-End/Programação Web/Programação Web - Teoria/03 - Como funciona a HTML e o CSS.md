### Para que serve HTML, CSS e JS?

Uma das coisas mais importantes para quem está começando o desenvolvimento de sites é compreender para que serve esse trio de tecnologias, que geralmente são estudados em conjunto. Basicamente, de forma resumida, temos um panorama simples:

> HTML - Conteúdo
> CSS - Estilo
> JavaScript - Interatividade

Guarde bem a tabela anterior sempre que você precisar decidir qual linguagem vai utilizar em cada situação. 

Abra aí o seu site de notícias favorito. Ao abrir uma determinada notícia, você vai ver o texto, as imagens, os vídeos e todo aquele conteúdo que compõe a notícia em si. Isso tudo foi criado em **HTML.** Ela é focada em **conteúdo.**

Agora preste atenção nas cores, na posição dos componentes e organização visual do conteúdo em colunas, blocos visuais e tudo mais. Tudo foi definido em **CSS.** Ela é focada no **design/estilo.** 

Finalmente, provavelmente existe o menu do site. Quando você clica nele, acontece uma animação. Ao mover o mouse sobre as sessões, é possível que aconteçam algumas interações interessantes. Isso foi desenvolvido com ajuda de JavaScript. Ela é uma linguagem focada nas **interações.**
____

### **Tags HTML**

Como eu já disse anteriormente, a HTML funciona baseada em marcações específicas chamadas tags. Uma tag é um conjunto de palavras entre sinais de colchete angular, conforme representado a seguir.

	<p>Exemplo de Paragrafo</p>

![[Pasted image 20221128201416.png]]

Na imagem anterior, você consegue perceber o uso da tag < p>para a criação de um parágrafo simples. A maioria das tags possuem uma **abertura** e um **fechamento**, e você identifica isso pela presença da barra no fechamento da tag. Além disso, as tags também podem ter atributos e valores, que vão configurar seu comportamento:

	<a href="destino.html">Exemplo de Link</a>

![[Pasted image 20221128201603.png]]

Uma mesma tag pode ter vários parâmetros, cada um com seu valor. Entretanto, algumas tags não possuem a necessidade de conteúdo interno e por isso não possuem fechamento. É o caso, por exemplo, das tags  
____

### Seletores CSS

Como já vimos anteriormente, as **CSS** são as **Cascading Style Sheets** (Folhas de Estilo em Cascata). Elas são usadas para configurar um **resultado visual** dos elementos HTML. 

As configurações das CSS são realizadas através dos **seletores**. Vamos ver a anatomia de um seletor.

	p {
		font-family: Arial;
		font-size: 12pt;
		color: blue;
	}

![[Pasted image 20221128201956.png]]

O seletor apresentado anteriormente vai configurar o visual dos elementos de parágrafo do site corrente. O uso das chaves delimita todas as declarações relativas ao seletor atual. No seletor que eu te mostrei, serão feitas três configurações: 
• A fonte escolhida foi Arial. 
• O tamanho da letra será 12pt (pontos). 
• A cor da letra será azul. 

Note que, ao final de cada **declaração**, temos que colocar ponto-e-vírgula para indicar que ela se encerrou. 

Todas as **propriedades** devem ter seu **valor**, e eles devem ser separados por dois pontos. Você não é obrigado(a) a usar nenhuma declaração específica. Só utilize a propriedade que você realmente deseja alterar.
### Estrutura Básica de um Documento HTML

Ao criar um novo documento HTML, devemos sempre escrever a estrutura básica de um documento desse formato. Vamos analisar cada uma das 11 linhas que compõem esse documento base.

	<!DOCTYPE html>
	<html lang="en">
		<head>
			<meta charset="UTF-8">
			<meta name="viewport" content="width=device-width, initial-scale=1.0">
			<title>Document</title>
		</head>
		<body>	
		</body>
	</html>

* **Linha 1:** Indica que o documento atual será escrito na versão mais atualizada da linguagem (no caso, HTML5) 
* **Linhas 2 e 11:** Delimitam o documento HTML, que é sempre dividido em duas partes: a cabeça e o corpo. Na linha 2, também estamos indicando que o conteúdo desse site será no idioma Português do Brasil. 
* **Linhas 3 e 7**: Delimitam a cabeça da página, local onde são realizadas algumas configurações iniciais como formatos, estilos, ícone de favoritos, etc. 
* **Linha 4:** adiciona ao documento atual o suporte a caracteres acentuados. Remover essa linha pode causar erros de renderização de algumas letras na tela. 
* **Linha 5:** Indica que o conteúdo aparecerá, por padrão, ocupando todo o espaço disponível da tela e com uma escala de 1:1. 
* **Linha 6:** Configura o título da página, que aparecerá como identificação da aba do navegador, ao lado do favicon. 
* **Linhas 8 e 10:** Delimitam o corpo da página, a maior porção do site, que vai aparecer na tela. É aqui onde colocaremos todo o nosso conteúdo.