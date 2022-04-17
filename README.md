# CineHouse

![Introdução a Node e Javascript](https://djament.com.br/assets/img/dh-m02-cover.png)

## Introdução

A ideia é que o tema de prática seja continuado até pelo menos o fim das 4 aulas deste módulo. A ideia é desenvolver mais e mais funcionalidades do cinema atrelado ao conteúdo recebido (adicionando nas próximas aulas array, funções e afins).

## Objetivo

O objetivo desta prática é que os alunos aprendam a iniciar um projeto node, executar arquivos, fazer download de uma biblioteca e começar a abordar o tema de modularização.

## Pré Requisitos

O que é necessário para acompanhar a prática?

* Ter as ferramentas instaladas em ambiente local (node.js, npm, VSCode, gitBash)

* Ter uma conta no gitHub (ou similar) para versionar o projeto

* Consumir o conteúdo do PlayGround

* Assistir as aulas síncronas

## Enunciados

Replicação dos enunciados para facilitar a compreensão dos exercícios e respectivas resoluções.

### Aula 01 | Introdução a NodeJS

Atividades relacionadas a aula 01.

#### Atividade 01

**Etapa 01**

No terminal, verificar se o node foi instalado.

```sh
node -v
```

**Etapa 02**

Criar pasta para o projeto, chamada CineHouse.

```sh
mkdir CineHouse
```

**Etapa 03**

Criar um arquivo chamado _cinema.js_. Nele, criar uma variável chamada `cinema` , que deverá receber o nome da loja (_string_).

_Criando (e abrindo) arquivo cinema.js:_

```sh
cd CineHouse && touch cinema.js && code cinema.js
```

_Criando a `const` cinema e atribuindo uma string a ela:_

```js
const cinema = "CineMarco"
```

#### Atividade 02

**Etapa 01**

Executar `npm init` (na pasta CineHouse) e verificar as mudanças que ocorreram na pasta e arquivos novos adicionados ao projeto.

_Executar o seguinte comando no terminal:_

```sh
cd CineHouse && npm init
```

_Responder às perguntas do diálogo no terminal conforme preferência._

**Etapa 02**

No arquivo _cinema.js_, passar a variável anteriormente criada como argumento do `console.log()` para visualizar o nome da loja no terminal ao executar o arquivo.

```js
console.log(cinema)
```

**Etapa 03**

Executar o arquivo _cinema.js_.

**Etapa 04**

Instalar o pacote _nodemon_.

**Etapa 05**

Analisar a pasta _node\_modules_.
