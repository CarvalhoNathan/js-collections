# Aula 1: Map - Coleções chaveadas

- Apresentar a coleção Map
- Explicar sua aplicação
- Diferença entre Map e Objeto

## Estrutura
```js
const myMap = new Map()
```

## Características:

- Uma coleção de arrays no formato ```[chave, valor]```.
- Pode iterado por um loop for...of.

# Métodos

## Adiciona, ler e deletar
```js
const myMap = new Map()

myMap.set('apple', 'fruit');
// Map(1) {"apple" => "fruit"}

myMap.get(apple);
// "fruit"

myMap.delete("apple"
// true

myMap.get("apple")
// undefined
```

# Map vs Objeto

- Maps podem ter chaves de qualquer tipo;
- Maps possuem a propriedade length;
- Maps são mais fáceis de iterar;
- Utilizado quando o valor de chaves é desconhecido;
- Os valores tem o mesmo tipo.

<p align="center">
  Readme by <a href="https://github.com/CarvalhoNathan"> Nathan Carvalho </a> <br>
</p>
