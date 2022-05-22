# ✨EXERCICIOS-5✨
## _Prof:Alexandre Carlos_

## ✨1 - DISPLAY✨
>- Defina os elementos como um flex container, tornando os seus filhos flex-itens.
<h1>display: block;</h1>
<section>
	<div>1</div>
	<div>2</div>
	<div>3</div>
	<div>4</div>
</section>
<hr>
<h1>display: flex;</h1>
<section class="container flex">
	<div>1</div>
	<div>2</div>
	<div>3</div>
	<div>4</div>
</section>
<hr>
<h1>display: flex;</h1>
<section>
	<div>Teste 1</div>
	<div>Teste 2</div>
	<div>Teste 3</div>
	<div>Teste 4</div>
	<div>Teste 5</div>
	<div>Teste 6</div>
	<div>Teste 7</div>
</section>
<hr>
<h1>display: flex;</h1>
<section>
	<div>Teste 1</div>
	<div>Teste 2</div>
	<div>Teste 3</div>
	<div>Teste 4</div>
	<div>Teste 5</div>
	<div>Teste 6</div>
	<div>Teste 7</div>
</section>
<hr>
<h1>display: flex; // flex-item-1</h1>
<section>
	<div>Teste 1</div>
	<div>Teste 2</div>
	<div>Teste 3</div>
</section>

## ✨2 - FLEX-DIRECTION✨
> - Defina a direção dos flex itens. Utilize row e columns. A mudança de row para column geralmente acontece quando estamos definindo os estilos em media queries para o mobile. Assim você garante que o conteúdo seja apresentado em coluna única ou em linha única.
<h1>flex-direction: row;</h1>
<section>
	<div>1</div>
	<div>2</div>
	<div>3</div>
</section>
<hr>
<h1>flex-direction: row-reverse;</h1>
<section>
	<div>1</div>
	<div>2</div>
	<div>3</div>
</section>
<hr>
<h1>flex-direction: column;</h1>
<section>
	<div>1</div>
	<div>2</div>
	<div>3</div>
</section>
<hr>
<h1>flex-direction: column-reverse;</h1>
<section>
	<div>1</div>
	<div>2</div>
	<div>3</div>
</section>

## ✨3 - FLEX-WRAP✨
>- Defina se os itens devem quebrar ou não a linha. Essa é geralmente uma propriedade que é quase sempre definida como flex-wrap: wrap; Pois assim quando um dos flex itens atinge o limite do conteúdo, o último item passa para a coluna debaixo e assim por diante.
<h1>flex-wrap: nowrap;</h1>
<section>
<!-- O nome grudado foi necessário pois eu preciso definir um conteúdo que não possa ser quebrado. Como uma palavra ou uma imagem. Se fosse uma frase, ele quebraria as linhas da frase antes de ultrapassar o container.	 -->
	<div>TesteDoItem1</div>
	<div>TesteDoItem2</div>
	<div>TesteDoItem3</div>
</section>
<hr>
<h1>flex-wrap: wrap;</h1>
<section class="container wrap">
	<div>TesteDoItem1</div>
	<div>TesteDoItem2</div>
	<div>TesteDoItem3</div>
</section>
<hr>
<h1>flex-wrap: wrap-reverse;</h1>
<section>
	<div>TesteDoItem1</div>
	<div>TesteDoItem2</div>
	<div>TesteDoItem3</div>
</section>

## ✨4 - JUSTIFY-CONTENT✨
>- Alinhe os itens flex no container de acordo com a direção. Excelente propriedade para ser usada em casos que você deseja alinhar um item na ponta esquerda e outro na direita, como em um simples header com marca e navegação.
<h1>justify-content: flex-start;</h1>
<section>
	<div>1</div>
	<div>Teste 2</div>
	<div>3</div>
	<div>4</div>
</section>
<hr>
<h1>justify-content: flex-end;</h1>
<section>
	<div>1</div>
	<div>Teste 2</div>
	<div>3</div>
	<div>4</div>
</section>
<hr>
<h1>justify-content: center;</h1>
<section>
	<div>1</div>
	<div>Teste 2</div>
	<div>3</div>
	<div>4</div>
</section>
<hr>
<h1>justify-content: space-between;</h1>
<section>
	<div>1</div>
	<div>Teste 2</div>
	<div>3</div>
	<div>4</div>
</section>
<hr>
<h1>justify-content: space-around;</h1>
<section>
	<div>1</div>
	<div>Teste 2</div>
	<div>3</div>
	<div>4</div>
</section>
<hr>
<h1>justify-content: space-around; // itens com flex: 1;</h1>
<section>
	<div>1</div>
	<div>Teste 2</div>
	<div>3</div>
	<div>4</div>
</section>
<hr>
<h1>justify-content: flex-start; // column</h1>
<section>
	<div>1</div>
	<div>Teste 2</div>
	<div>3</div>
	<div>4</div>
</section>
<hr>
<h1>justify-content: flex-end; // column</h1>
<section>
	<div>1</div>
	<div>Teste 2</div>
	<div>3</div>
	<div>4</div>
</section>
<hr>
<h1>justify-content: center; // column</h1>
<section>
	<div>1</div>
	<div>Teste 2</div>
	<div>3</div>
	<div>4</div>
</section>
<hr>
<h1>justify-content: space-between; // column</h1>
<section>
	<div>1</div>
	<div>Teste 2</div>
	<div>3</div>
	<div>4</div>
</section>
<hr>
<h1>justify-content: space-around; // column</h1>
<section>
	<div>1</div>
	<div>Teste 2</div>
	<div>3</div>
	<div>4</div>
</section>
<hr>
<h1>justify-content: space-around; // column // itens com flex: 1;</h1>
<section>
	<div>1</div>
	<div>Teste 2</div>
	<div>3</div>
	<div>4</div>
</section>
