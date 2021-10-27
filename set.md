# Aula 2: Set

- Apresentar a coleção Set
- Explicar sua aplicação
- Explicar diferença entre Set e Array

## Estrutura
```js
const myArray = [1, 1, 2, 2, 3, 4, 5];

const mySet = new Set(myArray);

Set(8) {1, 2, 3, 4, 5, ...}
 [[Entries]]
  0: 1
  1: 2
  2: 3
  3: 4
  4: 5
  size: (...)
  __proto__: Set
```

Sets são estruturas que armazenam apenas valores únicos.

## Métodos

### Adicionar, consultar e deletar
```js
const mySet = new Set();

mySet.add(1); // Adicionar
mySet.add(5);

mySet.has(1); // Consultar
// true

mySet.has(3);
// false

mySet.delete(5); // Deletar
```
## Set vs Array

- Possui valores únicos;
- Em vez da propriedade length, consulta-se o número de registros pela propriedade size;
- Não possui os métodos map, filter, reduce etc.
