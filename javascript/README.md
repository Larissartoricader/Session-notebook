### JavaScript-Notes

## Elementos

- Variable: uma afirmacao que contem um valor: `let myName = Larissa` Neste caso, o myName é o nome da varíavel.
- value: O valor de uma variável `const PI = 3.14` Neste caso, 3.14 é o value.
- Initialization = O valor inicial dado a uma variável. `var x = 150` Neste caso, toda a informacao é a inicializacao.
- Tipos de valores: Numbers, Strings, Arrays
  - Numbers: Valores números sao inseridos sem nenhum caracteres: `let x = 135`
  - Strings: Valors de Textos e sao inseridos entre "". `console.log myName = "Larissa"`
  - Array é um elemento que pode contem multiplos valores: `var Location = ["Bauru", "Rio de Janeiro", "Sao Paulo"];` - Neste caso, o array hospeda mais de um tipo de valor String (texto).
  - Array também pode hospedar vários objetos. Nese casso, os objetvos precisam se inseridos em {} e ainda separados‚ por vírgula: `var formulario = {Nome, Sobrenome, Idade};`
  - Objetos sao estrutua de dados que podem contem multiplos valores como propriedades e métodos. É quase uma forma de agrupar diferentes variaveis/valores de um mesmo tema.
- Funcoes: é uma acao de uma secao de codigos. `funcion myFuncaoName() {};`

## Atributos

- onclick - Esse atributo aplica uma funcao já determina a um botao quando clicado. `button1.onclick = goStore`
- innertext - Esse atributo aplica uma funcao já determina à um texto inserido no html. Ele pode alterar o string para outro string: `minhaFilha.innerText = "Matteu"`

Dica: _Utilizando o método querySeletor é possível especificar qual elemento em html/css deve sofrer uma alteracao através de um atributo (onclick ou innterText)_

## Variaveis

- Let: Essa variavéil pode receber um novo valor: `let myLastName = Sartori-Cader``
- Const: Essa variável nao pode receber um novo valor e é uma forma de seguraca de encontrar um erro, caso seja aplicado um novo valor a uma const. `const minhaFilha = Isabella;`

## Métodos

- querySelector: Uma forma de ligar o Javascript ao Html e CSS. Utilizando o querySelector é possível aplicar uma acao à um elemento do html/css através de uma procura automática pelo Javascript. O querySelector procura sempre o primeiro elemento em html/css que se aplica a regra: `const minhaFilha = document.querySelector("#Isabella");`
