<h1 align="center">
  <img align="center" alt="Imagem trybe" src="https://i.ibb.co/d4W2x4g/trybe.png" width="300px" />
</h1>

<h3 align="center">
  Curso realizado na Trybe - Edu Souza o/
</h3>

<blockquote align="center">“O caminho nunca é largo demais quando um amigo nos acompanha - Marcelli Cristina”</blockquote>

<h4 align="center">
  Repositório - Projeto Playground functions
</h4>

<br/>

<p align="center">
  <a href="https://github.com/EduSouza-programmer"    target="_blank">
    <img alt="Made by Eduardo Souza" src="https://img.shields.io/badge/made%20by-Edu%20Souza-%23F8952D">
  </a>&nbsp;
  <a href="https://edusouza-programmer.github.io/" target="_blank">
    <img alt="Github page Edu_Souza " src="https://img.shields.io/badge/Github%20page-Edu_Souza-orange">
  </a>&nbsp;
  <a href="#" >
    <img alt="License" src="https://img.shields.io/badge/license-MIT-%23F8952D">
  </a>
</p>

<p align="center">
  <a href="#rocket-Sobre-o-projeto">Sobre o projeto</a>&nbsp; &nbsp; |&nbsp; &nbsp;
  <a href="#postbox-Entrega"">Entrega</a>&nbsp; &nbsp; |&nbsp; &nbsp;
  <a href="#unlock-Licença">Licença</a>
</p>

## :rocket: Sobre o projeto

#### Playground functions

Durante sua carreira como pessoa desenvolvedora, é importante saber quebrar grandes problemas em problemas menores e utilizar a lógica de programação na resolução;

Conseguir aplicar lógica de programação na prática utilizando o JavaScript é algo que você vai fazer diariamente.
Você vai desenvolver funções seguindo os requisitos especificados para o correto comportamento de cada uma delas.

<!-- #### Screenshots:

<p align=center >
  <img height="210px"  src="./img/home_desktop.png"> &nbsp;
  <img height="235px" src="./img/mobile.png">
</p> -->

## :postbox: Entrega

#### :clipboard: Sumário

- <p><a href="#1"> :pushpin: 1.</a> Usando o operador &&</p>
- <p><a href="#2"> :pushpin: 2.</a> Área do triângulo</p>
- <p><a href="#3"> :pushpin: 3.</a> Dividindo a frase</p>
- <p><a href="#4"> :pushpin: 4.</a> Concatenação de strings</p>
- <p><a href="#5"> :pushpin: 5.</a> Pontos no futebol</p>
- <p><a href="#6"> :pushpin: 6.</a> Repetição do maior número</p>
- <p><a href="#7"> :pushpin: 7.</a> Caça ao rato</p>
- <p><a href="#8"> :pushpin: 8.</a> FizzBuzz</p>
- <p><a href="#9"> :pushpin: 9.</a> Codifique e Decodifique</p>
- <p><a href="#10"> :pushpin: 10.</a> Lista de tecnologias</p>
- <p><a href="#11"> :pushpin: 11.</a> Número de telefone</p>
- <p><a href="#12"> :pushpin: 12.</a> Condição de existência de um triângulo</p>
- <p><a href="#13"> :pushpin: 13.</a> Bem vindo ao Bar da Trybe!</p>

<br/>

## :books: Exercícios

### 1°

JavaScript possui um operador lógico `&&`, o qual recebe dois valores e retorna `true` se ambos os valores são verdadeiros, e retorna `false` se algum dos valores não o for.

Considerando isso, crie uma função chamada `compareTrue` que, ao receber dois booleanos:

- Retorne `true` se ambos os valores são verdadeiros;
- Retorne `false` se um ou ambos os parâmetros forem falsos.

Faça a função utilizando o operador `&&`.

#### Resposta:

<details>
 <summary> :pencil2: Código Javascript</summary>

```js
function compareTrue(a, b) {
  // seu código aqui
  return a && b;
}
```

</details>

<p align="right">
    <a href="#clipboard-Sumário">
    <img alt="Back Sumário" src="https://img.shields.io/badge/Back-Sum%C3%A1rio-orange">
  </a>
</p>

#

### 2°

Escreva uma função com o nome `calcArea` que receba um valor de base (chamado `base`) e outro de altura (chamado `height`) de um triângulo e retorne o cálculo da sua área.

Lembre-se que a área de um triângulo é calculada através da seguinte fórmula: (base * altura) / 2.

#### Resposta:

<details>
 <summary> :pencil2: Código Javascript</summary>

```js
function calcArea(base, height) {
  // seu código aqui
  return (base * height) / 2;
}
```

</details>

<p align="right">
    <a href="#clipboard-Sumário">
    <img alt="Back Sumário" src="https://img.shields.io/badge/Back-Sum%C3%A1rio-orange">
  </a>
</p>

#


### 3°

Escreva uma função com o nome `splitSentence`, a qual receberá uma string e retornará uma array de strings separadas por cada espaço na string original.

Exemplo: se a função receber a string `"go Trybe"`, o retorno deverá ser `['go', 'Trybe']`.

#### Resposta:

<details>
 <summary> :pencil2: Código Javascript</summary>

```js
function splitSentence(name) {
  // seu código aqui
  let arr = name.split(' ');
  return arr;

}
```

</details>

<p align="right">
    <a href="#clipboard-Sumário">
    <img alt="Back Sumário" src="https://img.shields.io/badge/Back-Sum%C3%A1rio-orange">
  </a>
</p>

#
### 4°

Escreva uma função com o nome `concatName` que, ao receber uma array de strings, retorne uma string com o formato `'ÚLTIMO ITEM, PRIMEIRO ITEM'`, independente do tamanho da array.

Isso quer dizer que, caso o parâmetro passado para `concatName` seja a Array ['Lucas', 'Cassiano', 'Ferraz', 'Paolillo'], a função deverá retornar `Paolillo, Lucas`.

#### Resposta:

<details>
 <summary> :pencil2: Código Javascript</summary>

```js
function concatName(names) {
  // seu código aqui
  return `${names[names.length - 1]}, ${names[0]}`;

}
```

</details>

<p align="right">
    <a href="#clipboard-Sumário">
    <img alt="Back Sumário" src="https://img.shields.io/badge/Back-Sum%C3%A1rio-orange">
  </a>
</p>

#
### 5°

Escreva uma função com o nome `footballPoints` que receba o número de vitórias (esse parâmetro deverá se chamar `wins`) e o número de empates (esse parâmetro deverá se chamar `ties`) e retorne a quantidade de pontos que o time marcou em um campeonato.

Para tanto, considere que cada vitória vale 3 pontos e cada empate vale 1 ponto.

#### Resposta:

<details>
 <summary> :pencil2: Código Javascript</summary>

```js
function footballPoints(wins, ties) {
  // seu código aqui
  return (wins * 3) + (ties * 1);
}
```

</details>

<p align="right">
    <a href="#clipboard-Sumário">
    <img alt="Back Sumário" src="https://img.shields.io/badge/Back-Sum%C3%A1rio-orange">
  </a>
</p>

#
### 6°

Escreva uma função chamada `highestCount` que, ao receber uma array de números, retorne  a quantidade de vezes que o maior deles se repete.

Exemplo: caso o parâmetro de `highestCount` seja uma array com valores `[9, 1, 2, 3, 9, 5, 7]`, a função deverá retornar `2`, que é a quantidade de vezes que o número `9` (maior número do array) se repete.

#### Resposta:

<details>
 <summary> :pencil2: Código Javascript</summary>

```js
function highestCount(arr) {
  // seu código aqui
  let contador = 1;
  console.log(
    arr.sort(function (a, b) {
      return b - a;
    }),
  );
  for (let i = 1; arr[i - 1] === arr[i]; i += 1) {
    contador += 1;
  }
  return contador;
}
```

</details>

<p align="right">
    <a href="#clipboard-Sumário">
    <img alt="Back Sumário" src="https://img.shields.io/badge/Back-Sum%C3%A1rio-orange">
  </a>
</p>

#
### 7°

Imagine que existem dois gatos, os quais chamaremos de `cat1` e `cat2`, e que ambos estão atrás de um rato chamado `mouse`. Imagine que cada um dos três animais está em uma posição representada por um número.

Sabendo disso, crie uma função chamada `catAndMouse` que, ao receber a posição de `mouse`, `cat1` e `cat2`, **nessa ordem**, calcule as distâncias entre o rato e os gatos e retorne qual dos felinos irá alcançar o rato primeiro (sendo aquele que estará mais perto).

Exemplo: caso o gato `cat2` esteja a 2 unidades de distância do rato, e `cat1` esteja a 3 unidades, sua função deverá retornar `cat2`.

Caso os gatos estejam na mesma distância do rato, a função deverá retornar a string `"os gatos trombam e o rato foge"`.

#### Resposta:

<details>
 <summary> :pencil2: Código Javascript</summary>

```js
function catAndMouse(mouse, cat1, cat2) {
  // seu código aqui
  let cat1Pos = Math.abs(mouse - cat1);
  let cat2Pos = Math.abs(mouse - cat2);
  if (cat1Pos < cat2Pos) {
    return 'cat1';
  } else if (cat1Pos > cat2Pos) {
    return 'cat2';
  }
  return 'os gatos trombam e o rato foge';
}
```

</details>

<p align="right">
    <a href="#clipboard-Sumário">
    <img alt="Back Sumário" src="https://img.shields.io/badge/Back-Sum%C3%A1rio-orange">
  </a>
</p>

#
### 8°

Crie uma função chamada `fizzBuzz` que receba uma array de números e retorne uma array da seguinte forma:

- Para cada número da Array que seja divisível apenas por 3, apresente uma string `"fizz"`;
- Para cada número da Array que seja divisível apenas por 5, apresente uma string `"buzz"`;
- Caso o número seja divisível por 3 e 5, retorne a string `"fizzBuzz"`;
- Caso o número não possa ser dividido por 3 nem por 5, retorne a string `"bug!"`;

Exemplo: caso o parâmetro seja [2, 15, 7, 9, 45], sua função deverá retornar `["bug!", "fizzBuzz", "bug!", "fizz", "fizzBuzz"]`.

#### Resposta:

<details>
 <summary> :pencil2: Código Javascript</summary>

```js
function fizzBuzz(arr) {
  // seu código aqui
  let arrResult = [];

  for (let value of arr) {
    if (value % 3 === 0 && value % 5 === 0) {
      arrResult.push('fizzBuzz');
    } else if (value % 3 === 0) {
      arrResult.push('fizz');
    } else if (value % 5 === 0) {
      arrResult.push('buzz');
    } else {
      arrResult.push('bug!');
    }
  }
  return arrResult;
}

```

</details>

<p align="right">
    <a href="#clipboard-Sumário">
    <img alt="Back Sumário" src="https://img.shields.io/badge/Back-Sum%C3%A1rio-orange">
  </a>
</p>

#
### 9°

Crie duas funções: a primeira deverá se chamar `encode` e, ao receber uma string como parâmetro, deverá trocar todas as vogais minúsculas por números, de acordo com o formato a seguir:

a -> 1 \
e -> 2 \
i -> 3 \
o -> 4 \
u -> 5

Ou seja, caso o parâmetro de `encode` seja `"hi there!"`, o retorno deverá ser `"h3 th2r2!"`.

A segunda função deverá se chamar `decode` e faz o contrário de `encode` - ou seja, recebe uma string contendo números no lugar de letras minúsculas e retornará uma string com vogais minúsculas no lugar dos números (então, caso o parâmetro de `decode` seja `"h3 th2r2!"`, o retorno deverá ser `"hi there!"`).

#### Resposta:

<details>
 <summary> :pencil2: Código Javascript</summary>

```js
function encode(arg) {
  // seu código aqui
  let code = ['a', 'e', 'i', 'o', 'u'];
  for (let i = 1; i <= code.length; i += 1) {
    arg = arg.replace(RegExp(code[i - 1], 'g'), i);
  }
  return arg;
}

function decode(arg) {
  // seu código aqui
  let code = ['a', 'e', 'i', 'o', 'u'];
  for (let i = 1; i <= code.length; i += 1) {
    arg = arg.replace(RegExp(i.toString(), 'g'), code[i - 1]);
  }
  return arg;
}

```

</details>

<p align="right">
    <a href="#clipboard-Sumário">
    <img alt="Back Sumário" src="https://img.shields.io/badge/Back-Sum%C3%A1rio-orange">
  </a>
</p>

#
### 10°

Crie uma função que recebe um array de nomes de tecnologias que você quer aprender. Essa função deve receber também um segundo parâmetro chamado `name` com um nome.

Para cada tecnologia no array, crie um objeto com a seguinte estrutura:

```
{
  tech: "NomeTech",
  name: name
}
```

Estes objetos devem ser inseridos em uma nova lista em ordem crescente a partir do campo `tech` no objeto.

A saída da sua função deve ser uma lista de objetos ordenada pelo campo `tech` dos objetos com o formato acima.

Exemplo:
```
Entradas da função:

["React", "Jest", "HTML", "CSS", "JavaScript"]
"Lucas"

// Saída:

[
  {
    tech: "CSS",
    name: "Lucas"
  },
  {
    tech: "HTML",
    name: "Lucas"
  },
  {
    tech: "JavaScript",
    name: "Lucas"
  },
  {
    tech: "Jest",
    name: "Lucas"
  },
  {
    tech: "React",
    name: "Lucas"
  }
]
```

Caso o array venha vazio sua função deve retornar 'Vazio!'

#### Resposta:

<details>
 <summary> :pencil2: Código Javascript</summary>

```js
function techList(argArray, name) {
  // seu código aqui
  if (argArray.length === 0) {
    return 'Vazio!';
  }

  let resultArray = [];
  argArray.sort();
  for (let argName of argArray) {
    let resultObject = {
      tech: argName,
      name: `${name}`,
    };
    resultArray.push(resultObject);
  }
  return resultArray;
}
```

</details>

<p align="right">
    <a href="#clipboard-Sumário">
    <img alt="Back Sumário" src="https://img.shields.io/badge/Back-Sum%C3%A1rio-orange">
  </a>
</p>

#
### 11°

Crie uma função chamada `generatePhoneNumber` que receba uma array com 11 números e retorne um número de telefone, respeitando parênteses, traços e espaços.

Exemplo: caso o parâmetro da função seja [1, 2, 3, 4, 5, 6, 7, 8, 9, 0, 1], `generatePhoneNumber` deverá retornar `(12) 34567-8901`.

- Se a função receber um array com tamanho diferente de 11, a mesma deve retornar `"Array com tamanho incorreto."`.

- Caso algum dos números da array seja menor que 0, maior que 9 ou se repita 3 vezes ou mais, `generatePhoneNumber` deverá retornar a string `"não é possível gerar um número de telefone com esses valores"`.

#### Resposta:

<details>
 <summary> :pencil2: Código Javascript</summary>

```js
// Help 11
function checkLength(numberArray) {
  let result = '';
  // check length
  if (numberArray.length !== 11) {
    result = 'Array com tamanho incorreto.';
  }
  return result;
}

// Help 11
function checkNumbers(numberArray) {
  let result = '';
  // check rule < 0 OR > 9
  for (let number of numberArray) {
    if (number < 0 || number > 9) {
      result = 'não é possível gerar um número de telefone com esses valores';
    }
  }
  return result;
}

// Help 11
function checkRepeat(numberArray) {
  let result = '';
  // chek rule repeat 3 times or more
  let numberArraySorted = numberArray.slice(0);
  numberArraySorted.sort(function (a, b) { return a - b });
  for (let i = 0; i <= 8; i += 1) {
    if (numberArraySorted[i] === numberArraySorted[i + 2]) {
      result = 'não é possível gerar um número de telefone com esses valores';
    }
  }
  return result;
}

// Desafio 11
function generatePhoneNumber(numberArray) {
  let result = '';
  result = checkLength(numberArray);
  if (result.length === 0) {
    result = checkNumbers(numberArray);
  }
  if (result.length === 0) {
    result = checkRepeat(numberArray);
  }
  if (result.length === 0) {
    // format number
    let textDDD = numberArray.slice(0, 2).join('');
    let textBegin = numberArray.slice(2, 7).join('');
    let textEnd = numberArray.slice(7).join('');
    result = `(${textDDD}) ${textBegin}-${textEnd}`;
  }
  return result;
}
```

</details>

<p align="right">
    <a href="#clipboard-Sumário">
    <img alt="Back Sumário" src="https://img.shields.io/badge/Back-Sum%C3%A1rio-orange">
  </a>
</p>

#
### 12°

Um triângulo é composto de três linhas: `lineA`, `lineB` e `lineC`. Crie uma função chamada `triangleCheck` que deverá receber as três linhas como parâmetro e retornar se é possível formar um triângulo com os valores apresentados de cada linha

Para tanto, tenha em mente algumas considerações:

- Para que seja possível formar um triângulo, é necessário que a medida de qualquer um dos lados seja menor que a soma das medidas dos outros dois e maior que o valor absoluto da diferença entre essas medidas.

- Para obter o valor absoluto de um número em JavaScript, pesquise pela função `Math.abs`.

- O retorno da sua função deverá ser um booleano.

Exemplo: o retorno de `triangleCheck(10, 14, 8)` deverá ser `true`.

#### Resposta:

<details>
 <summary> :pencil2: Código Javascript</summary>

```js
function triangleCheck(linhaA, linhaB, linhaC) {
  // seu código aqui
  let checkA = linhaA < linhaB + linhaC && linhaA > Math.abs(linhaB - linhaC);
  // check linhaB
  let checkB = linhaB < linhaA + linhaC && linhaB > Math.abs(linhaA - linhaC);
  // check linhaC
  let checkC = linhaC < linhaB + linhaA && linhaC > Math.abs(linhaB - linhaA);

  return checkA && checkB && checkC;
}
```

</details>

<p align="right">
    <a href="#clipboard-Sumário">
    <img alt="Back Sumário" src="https://img.shields.io/badge/Back-Sum%C3%A1rio-orange">
  </a>
</p>

#
### 13°

-
Segundo as regras desse bar, a cada bebida deve-se beber um copo de água para que não se tenha ressaca.

Crie a função `hydrate` que recebe uma string, e retorne a sugestão de quantos copos de água você deve beber. Exemplos:
```
String recebida:
  "1 cerveja"
String retornada:
  "1 copo de água"
```

```
String recebida:
  "1 cachaça, 5 cervejas e 1 copo de vinho"
String retornada:
  "7 copos de água"
```

```
String recebida:
  "1 cachaça, 5 cervejas e 1 copo de vinho"
String retornada:
  "7 copos de água"
```

**Notas**

- Para simplificar, consideraremos que qualquer coisa com um número à frente é uma bebida **e que a sua string sempre virá com o formato quantidade (em número) + tipo da bebida**.

- O número na frente de cada bebida está no intervalo entre 1 e 9.

**Dica:** pesquise por algo similar a `get all integers inside a string js`.

#### Resposta:

<details>
 <summary> :pencil2: Código Javascript</summary>

```js
function hydrate(drink) {
  // seu código aqui
  let amountOfDrinks = drink.match(/\d+/g).map(Number);
  let glassOfWater = amountOfDrinks.reduce((a, b) => a + b, 0);
  let result = '';
  if (glassOfWater === 1) {
    result = `${glassOfWater} copo de água`;
  } else {
    result = `${glassOfWater} copos de água`;
  }
  return result;
}
```

</details>

<p align="right">
    <a href="#clipboard-Sumário">
    <img alt="Back Sumário" src="https://img.shields.io/badge/Back-Sum%C3%A1rio-orange">
  </a>
</p>

<br/>

## :unlock: Licença

Este projeto está licenciado sob a Licença MIT - consulte [LICENSE](https://opensource.org/licenses/MIT) para maiores detalhes.
