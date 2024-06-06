# Type Conversion (conversão de tipo) / Type coercion (coerção de tipo)

```js

var x = Number("0") //Type Conversion, nessa linha é feita uma conversão de tipo explicita
var y = "2" +3// Type Coersion, nessa linha é feita uma conversão implicito do valor 3 que é númerico(number) para texto (string)

//Onde usa expressões condicional e repetição, faz necessário um valor boolean (verdadeiro ou falso)
//Ex.
if(true) {
}

//Caso não for informado uma expressão ou um valor boolean diretamente, ele fará um Type Coercion (Coerção de tipo)
//Ex.
if(0) { //Nessa linha ele ira fazer uma conversão do 0 para um boolean (verdadeiro ou falso), nesse caso 0 será falso
}
```
