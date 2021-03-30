# Estudando Flex-box

<p align="center">Estudo para fixar as propriedades e possíveis aplicações do flexbox e evitar perder tempo durante a execução do projeto, tentando lembrar qual propriedade do flex box usar.</p>
<p align="center">Este projeto foi desenvolvido seguindo um tutorial da RocketSeat 🚀 </p>

<p align="center">
 <a href="#objetivo">Objetivo</a> •
 <a href="#telas-da-aplicacao">Telas da Aplicação</a> •
 <a href="#conceitos">Revisão de Conceitos</a> •
 <a href="#tecnologias">Tecnologias</a> •
 <a href="#referencias">Referências</a> •
 <a href="#licenc-a">Licença</a> •
 <a href="#autor">Autor</a>
</p>

<h4 align="center">
	🚧  Página inicial do Twitter 🚀 Em construção...  🚧
</h4>

### Objetivo
<p>Recriar a tela inicial do Twitter usando flexbox para organizar todos os elementos.</p>

### Telas da Aplicação

<h1 align="center">
  <img alt="Tela inicial do Twitter"  src="/images/screenshot.png" />
</h1>

### Conceitos

#### PROPRIEDADES USADAS NO CONTAINER.
  <p><b>display flex:</b> alinha os itens horizontalmente;</p>
  <p><b>flex-direction:</b> row, alinha os elementos pela linha por padrão;</p>
  <p><b>flex-direction:</b> column, alinha os elementos pela coluna;</p>
  <p><b>flex-direction:</b> row-reverse, alinha os elementos em linha começando pelo final da linha;</p>
  <p><b>flex-direction:</b> column-reverse, alinha os elementos em linha começando pelo final da coluna;</p>
  </br>
  <p><b>align-items:</b> alinha os elementos verticalmente (se o flex-direction está em row);</p>
  <p><b>align-items:</b> flex-start; alinhando os itens no começo da página;</p>
  <p><b>align-items:</b> flex-end; alinhando os itens verticalmente  no fim da página;</p>
  <p><b>align-items:</b> center; alinhando os itens verticalmente  ao centro da página;</p>
  <p><b>align-items:</b> alinha os elementos horizontalmente (se o flex-direction está em column);;</p>

  <p>O <b>ALIGN-ITEMS</b> alinha os elementos na direção oposta ao FLEX-DIRECTION.</p>
  <p>O <b>JUSTIFY-CONTENT</b> alinha os elementos na mesma direção do FLEX-DIRECTION.</p>
  </br>
  <p><b>justify-content:</b> alinhará os itens horizontalmente.
  <p><b>justify-content:</b> flex-start; alinhando os itens no começo da página</p>
  <p><b>justify-content:</b> flex-end; alinhando os itens horizontalmente no fim da página</p>
  <p><b>justify-content:</b> center; alinhando os itens horizontalmente ao centro da página</p>
  <p><b>justify-content:</b> space-between; espaça igualmente entre os elementos;</p>
  <p><b>justify-content:</b> space-around; espaça igulamente entre os elementos e antes e depois;</p>
  </br>
  <p><b>flex-wrap:</b> wrap; mantem o tamanho padrão e quebra a linha se necessário. Sem o wrap ele usa o shrink por padrão e diminui o elemento.</p>
  <p><b>flex-wrap:</b> (wrap, wrap-reverse);</p>
  </br>
  <p><b>align-content:</b> center; propriedade igual ao justify-content mas usada quando os elementos tem quebra de linha.</p>
  <p><b>align-content:</b> (flex-start, flex-end, center, space-between, space-arownd);</p>
  </br>

#### PROPRIEDADES USADAS NO BOX
  <p><b>flex-grow:</b> 1, o elemento aceita ser aumentado para ocupar o tamanho total do elemento pai;</p>
  <p><b>flex-shrink:</b> 1, o elemento pode ser expremido para caber na tela.</p>
  <p><b>flex-shrink:</b> 0, o elemento fica fixo e não pode ser expremido para caber na tela.</p>

  <p><b>flex:</b> 1 0; quando usar somente flex o primeiro valor representa o grow e o segundo o shrink,
  é usado quando quer que o elemento se estique para caber e não se encolha quando a tela diminuir.</p>
<p><b>ORDER</b></p>
  <p>Propriedade que pode ser setada em cada elemento, geralmente é usada quando a depender da largura da tela os elementos precisem mudar de lugar, ou inverter a ordem.</p>

### 🛠 Tecnologias

As seguintes ferramentas foram usadas na construção do projeto:

- [HTML](https://expo.io/)
- [CSS](https://nodejs.org/en/)
- [JavaScript](https://pt-br.reactjs.org/)

## Referências
<p><a href="https://css-tricks.com/snippets/css/a-guide-to-flexbox/">CSS Tricks<a></p>
<p><a href="https://cssreference.io/flexbox/">CSSReference.io<a></p>
<p><a href="https://blog.rocketseat.com.br/como-fazer-um-bom-readme/">Rockeat Seat - como fazer um bom readme</a></p>

## Licença

## Autora
