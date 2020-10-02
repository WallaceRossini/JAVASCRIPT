# Array Methods

## Push
O método `push()` adiciona novos elementos
ao final de uma matriz e retorna o novo comprimento. 


```js 
  const arr = ["Coding", "With"];
  arr.push("Evan");

  ["Coding","With","Evan"]
```

## Slice
O método `slice()` seleciona uma parte de
uma matriz e retorna a nova matriz.

```js 
  const arr = ["Coding", "With", "Evan"];
  arr.slice(1, 2);

  ["With"]
```

## ToString
O método `toString()` converte um array em uma string.

```js 
  const arr = ["Coding", "With", "Evan"];
  arr.toString();

  "Coding","With","Evan"
```

## Shift
O método `shift()` remove o primeiro elemento de uma matriz.

```js
  const arr = ["Coding", "With", "Evan"];
  arr.shift();

  ["With","Evan"]
```

##  Map
O método `map()` cria uma nova matriz com o resultado
de chamar uma função para cada elemento do array.

```js
  const arr = [2, 4, 6, 8];
  arr.map(x => x * 2);

  [4, 8, 12, 16]
```

## Pop
O método `pop()` remove o último elemento
de uma matriz.

```js
  const arr = ["Coding", "With", "Evan"];
  arr.pop();

  ["Coding","With"]
```

## Filter
O método `filter()` cria um array preenchido com
todos elementos da matriz que passam em um teste.

```js
  const arr = ["Coding", "With", "Evan"];
  arr.filter(word => word.length > 4);  

  ["Conding"]
```
## Includes
O método `includes()` determina se um
array contém um elemento especificado.

```js
const arr = ["Coding", "With", "Evan"];
arr.includes("Evan");

true
```