# JAVASCRIPT

## Introdução 

### Variáveis e dados

```js
 var nome = "Wallace"; // String
 var idade = 18; // Int
 var peso = 58.6; // Float
 var humano = true; // Boolean
 var frutas = ['Morango','Uva','Limão']; // Array 
 var aluno = { nome: 'Wallace', idade: 18, peso: 58.6, humano: true }; // Object

frutas[0] // Morango
aluno.nome // Wallace
```

### Operações matemáticas
```js 
  var x = 10, y = 5;
  console.log(x ,y); // 10 5

  // Adição
  x += 3; // 13 
  //Subtração
  x -= 3; // 7
  //Multiplicação
  x *= 3; // 30
  //Divisão
  x /= 3; // 3.33...
  //Resto de divisão
  x %= 3; // 1

  var resultado = x + y; // 15
```

### Funções
```js 

  function soma(num_1, num_2){
    return num_1 + num_2;
  }
  soma(1,2) // 3

```

### Condicionais

*==* Compara se os valores são iguais.
*===* Compara se os valores são iguais e se o tipo de dado também é.

```js 
  if(sexo == 'M')
    return 'Masculino';
  else
    return 'Feminino';

  switch(sexo)
 
```

## Array Methods

### Push
O método `push()` adiciona novos elementos
ao final de uma matriz e retorna o novo comprimento. 


```js 
  const arr = ["Coding", "With"];
  arr.push("Evan");

  ["Coding","With","Evan"]
```

### Slice
O método `slice()` seleciona uma parte de
uma matriz e retorna a nova matriz.

```js 
  const arr = ["Coding", "With", "Evan"];
  arr.slice(1, 2);

  ["With"]
```

### ToString
O método `toString()` converte um array em uma string.

```js 
  const arr = ["Coding", "With", "Evan"];
  arr.toString();

  "Coding","With","Evan"
```

### Shift
O método `shift()` remove o primeiro elemento de uma matriz.

```js
  const arr = ["Coding", "With", "Evan"];
  arr.shift();

  ["With","Evan"]
```

### Map
O método `map()` cria uma nova matriz com o resultado
de chamar uma função para cada elemento do array.

```js
  const arr = [2, 4, 6, 8];
  arr.map(x => x * 2);

  [4, 8, 12, 16]
```

### Pop
O método `pop()` remove o último elemento
de uma matriz.

```js
  const arr = ["Coding", "With", "Evan"];
  arr.pop();

  ["Coding","With"]
```

### Filter
O método `filter()` cria um array preenchido com
todos elementos da matriz que passam em um teste.

```js
  const arr = ["Coding", "With", "Evan"];
  arr.filter(word => word.length > 4);  

  ["Conding"]
```
### Includes
O método `includes()` determina se um
array contém um elemento especificado.

```js
const arr = ["Coding", "With", "Evan"];
arr.includes("Evan");

true
```