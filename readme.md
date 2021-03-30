# Estudando Flex-box

<p align="center">Estudo para fixar as propriedades e possíveis aplicações do flexbox e evitar perder tempo durante a execução do projeto, tentando lembrar qual propriedade do flex box usar.</p>
<p align="center">Este projeto foi desenvolvido seguindo um tutorial da RocketSeat 🚀 </p>

<p align="center">
  <img src="https://img.shields.io/github/license/maite-marques/study-flexbox" alt="Badge License">
</p>

<p align="center">
 <a href="#objetivo">Objetivo</a> •
 <a href="#telas-da-aplicacao">Telas da Aplicação</a> •
 <a href="#conceitos">Revisão de Conceitos</a> •
 <a href="#tecnologias">Tecnologias</a> •
 <a href="#referencias">Referências</a>
</p>

<h4 align="center">Página inicial do Twitter 🚀</h4>

### Objetivo
<p>Recriar a tela inicial do Twitter de maneira simplificada usando apenas html e css com flexbox para organizar todos os elementos.</p>

### Telas da Aplicação

<h1 align="center">
  <img alt="Tela inicial do Twitter"  src="/images/screencapture.png" />
</h1>

### Conceitos

#### PROPRIEDADES USADAS NO CONTAINER.
<ul> 
	<li><b>display: flex</b> - alinha os itens horizontalmente.</li>
	<li><b>flex-direction: row</b> - alinha os elementos pela linha por padrão.</li>
	<li><b>flex-direction: column</b> - alinha os elementos pela coluna.</li>
	<li><b>flex-direction: row-reverse</b> - alinha os elementos em linha começando pelo final da linha.</li>
	<li><b>flex-direction: column-reverse</b> - alinha os elementos em linha começando pelo final da coluna.</li>
	</br>
	<li><b>align-items</b> - alinha os elementos verticalmente (se o flex-direction está em row e horizontalmente se o flex-direction está em column).</li>
	<li><b>align-items: flex-start</b> - alinhando os itens no começo da página.</li>
	<li><b>align-items: flex-end</b> - alinhando os itens verticalmente  no fim da página.</li>
	<li><b>align-items: center</b> - alinhando os itens verticalmente  ao centro da página.</li>

</ul>
  <p>O <b>ALIGN-ITEMS</b> alinha os elementos na direção oposta ao FLEX-DIRECTION.</p>
  <p>O <b>JUSTIFY-CONTENT</b> alinha os elementos na mesma direção do FLEX-DIRECTION.</p>
<ul>
	<li><b>justify-content:</b> alinhará os itens horizontalmente.</li>
  <li><b>justify-content: flex-start</b> alinhando os itens no começo da página.</li>
  <li><b>justify-content: flex-end</b> alinhando os itens horizontalmente no fim da página.</li>
  <li><b>justify-content: center</b> alinhando os itens horizontalmente ao centro da página.</li>
  <li><b>justify-content: space-between</b> espaça igualmente entre os elementos.</li>
  <li><b>justify-content: space-around</b> espaça igulamente entre os elementos e antes e depois.</li>
  </br>
  <li><b>flex-wrap: wrap</b> - mantem o tamanho padrão e quebra a linha se necessário. Sem o wrap ele usa o shrink por padrão e diminui o elemento.</li>
  <li><b>flex-wrap:</b> (wrap, wrap-reverse).</li>
  </br>
  <li><b>align-content: center</b> - propriedade igual ao justify-content mas usada quando os elementos tem quebra de linha.</li>
  <li><b>align-content:</b> (flex-start, flex-end, center, space-between, space-arownd).</li>
</ul>

#### PROPRIEDADES USADAS NO BOX
<ul>
  <li><b>flex-grow: 1</b> - o elemento aceita ser aumentado para ocupar o tamanho total do elemento pai.</li>
  <li><b>flex-shrink: 1</b> - o elemento pode ser expremido para caber na tela.</li>
  <li><b>flex-shrink: 0</b> - o elemento fica fixo e não pode ser expremido para caber na tela.</li>
  <li><b>flex: 1 0</b> - quando usar somente flex o primeiro valor representa o grow e o segundo o shrink,
  é usado quando quer que o elemento se estique para caber e não se encolha quando a tela diminuir.</li>
</ul>
</br>
<p><b>ORDER</b></p>
  <p>Propriedade que pode ser setada em cada elemento, geralmente é usada quando a depender da largura da tela os elementos precisem mudar de lugar, ou inverter a ordem.</p>

### 🛠 Tecnologias
As seguintes ferramentas foram usadas na construção do projeto:

- [HTML](https://expo.io/)
- [CSS](https://nodejs.org/en/)

### Referências
<p><a href="https://css-tricks.com/snippets/css/a-guide-to-flexbox/">CSS Tricks<a></p>
<p><a href="https://cssreference.io/flexbox/">CSSReference.io<a></p>
<p><a href="https://blog.rocketseat.com.br/como-fazer-um-bom-readme/">Rockeat Seat - como fazer um bom readme</a></p>
