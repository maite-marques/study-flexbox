# Estudando Flex-box

## Descrição do projeto
<p align="center">O objetivo deste estudo é evitar a perda de tempo tentando lembrar qual propriedade do flex box usar.</p>

<h1 align="center">
  <a href=""> Flex Box<a>
</h1>

Tabela de Conteúdos
================================================
<!--ts-->
  * [Sobre](#Sobre)
  * [Tabela de Conteúdo](#tabela-de-conteudo)
  * [Instalação](#instalacao)
  * [Como usar](#como-usar)
    * [Pré Requisitos](#pre-requisitos)
      * [Local files](#local-files)
      * [Remote files](#remote-files)
      * [Multiple files](#multiple-files)
      * [Combo](#combo)
   * [Tests](#testes)
   * [Tecnologias](#tecnologias)
<!--te-->

ou in line

<p align="center">
 <a href="#objetivo">Objetivo</a> •
 <a href="#roadmap">Roadmap</a> •
 <a href="#tecnologias">Tecnologias</a> •
 <a href="#contribuicao">Contribuição</a> •
 <a href="#licenc-a">Licença</a> •
 <a href="#autor">Autor</a>
</p>

<h4 align="center">
	🚧  Página inicial do Twitter 🚀 Em construção...  🚧
</h4>

### Conceitos

#### PROPRIEDADES USADAS NO CONTAINER.
 <p>display flex: alinha os itens horizontalmente
  flex-direction: row, alinha os elementos pela linha por padrão
  flex-direction: column, alinha os elementos pela coluna
  flex-direction: row-reverse, alinha os elementos em linha começando pelo final da linha
  flex-direction: column-reverse, alinha os elementos em linha começando pelo final da coluna</p>
  <p>
  align-items: alinha os elementos verticalmente (se o flex-direction está em row);
  align-items: flex-start; alinhando os itens no começo da página
  align-items: flex-end; alinhando os itens verticalmente  no fim da página
  align-items: center; alinhando os itens verticalmente  ao centro da página

  align-items: alinha os elementos horizontalmente (se o flex-direction está em column);

  O ALIGN-ITEMS alinha os elementos na direção oposta ao FLEX-DIRECTION.
  O JUSTIFY-CONTENT alinha os elementos na mesma direção do FLEX-DIRECTION.

  justify-content: alinhará os itens horizontalmente.
  justify-content: flex-start; alinhando os itens no começo da página
  justify-content: flex-end; alinhando os itens horizontalmente no fim da página
  justify-content: center; alinhando os itens horizontalmente ao centro da página
  justify-content: space-between; espaça igualmente entre os elementos;
  justify-content: space-around; espaça igulamente entre os elementos e antes e depois;

  flex-wrap: wrap; mantem o tamanho padrão e quebra a linha se necessário. Sem o wrap ele usa o shrink por
                   padrão e diminui o elemento.
  flex-wrap: (wrap, wrap-reverse);

  align-content: center; propriedade igual ao justify-content mas usada quando os elementos tem quebra de
                  linha.
  align-content: (flex-start, flex-end, center, space-between, space-arownd);
  </p>


#### PROPRIEDADES USADAS NO BOX
  <p>flex-grow: 1, o elemento aceita ser aumentado para ocupar o tamanho total do elemento pai;
  flex-shrink: 1, o elemento pode ser expremido para caber na tela.
  flex-shrink: 0, o elemento fica fixo e não pode ser expremido para caber na tela.

  flex: 1 0; quando usar somente flex o primeiro valor representa o grow e o segundo o shrink,
  é usado quando quer que o elemento se estique para caber e não se encolha quando a tela diminuir.
</p>
<p>
  ORDER
  Propriedade que pode ser setada em cada elemento, geralmente é usada quando a depender da largura da tela os elementos precisem mudar de lugar, ou inverter a ordem.
</p>

### Features

- [x] Cadastro de usuário
- [x] Cadastro de cliente
- [ ] Cadastro de produtos

### Print ou demonstração da aplicação

<h1 align="center">
  <img alt="NextLevelWeek" title="#NextLevelWeek" src="./assets/banner.png" />
</h1>

### 🛠 Tecnologias

As seguintes ferramentas foram usadas na construção do projeto:

- [Expo](https://expo.io/)
- [Node.js](https://nodejs.org/en/)
- [React](https://pt-br.reactjs.org/)
- [React Native](https://reactnative.dev/)
- [TypeScript](https://www.typescriptlang.org/)

## References
<p><a href="https://css-tricks.com/snippets/css/a-guide-to-flexbox/">CSS Tricks<a></p>
<p><a href="https://cssreference.io/flexbox/">CSSReference.io<a></p>
<p><a href="https://blog.rocketseat.com.br/como-fazer-um-bom-readme/">Rockeat Seat - como fazer um bom readme</a></p>
