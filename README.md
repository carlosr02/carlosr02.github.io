// Código que pode gerar uma exceção.
}
catch (Exception ex)
{
// Código para tratar exceção
}
finally
{
//
}
```
<h4>Criar novas exeções</h4>

Podemos criar nossas próprias exceções usando a palavra-chave **throw**.

```
try {
  throw new EvalError("some Message");
} catch (e) {
  console.log(e instanceof EvalError); // true
  console.log(e.message);              // some Message
  console.log(e.name);                 // "EvalError"
  
}
```
<h2>Sintaxe Funcional</h2>

Programação funcional é, primeiramente, escrever programas com funções genéricas reutilizáveis. Para construir um código em TypeScript segundo o paradigma funcional, deve-se seguir três técnicas:

* Usar funções em vez de valores simples;
* Modelar tranformações de dados como uma pipeline;
* Extrair funções genéricas.

Além do formato padrão de declaração de funções, TypeScript tem uma forma diferente de declaração conhecida como **lambda** ()=>{}.
<h3>Formato padrão</h3>

```
function isBigEnough(value) {
  return value >= 10;
}
var filtered = [12, 5, 8, 130, 44].filter(isBigEnough);
```
<h3>Syntaxe lambda</h3>

```
var isBigEnough = (value) => value >= 10;
var filtered = [12, 5, 8, 130, 44].filter(isBigEnough);
```
<h3>Outro formato</h3>

```
var filtered = [12, 5, 8, 130, 44].filter((value) => value >= 10);
```
<h2>Referências</h2>

* [TypeScript](https://www.typescriptlang.org/index.html)
* [TypeScript Tutorial](https://www.tutorialspoint.com/typescript)
* [Error Handling in Typescript](https://narayanatechnicalworld.blogspot.com.br/2016/05/error-handling-in-typescript.html)
* [Try Catch Statement in TypeScript](http://www.c-sharpcorner.com/UploadFile/5089e0/try-catch-statement-in-typescript/)
* [Functional TypeScript](https://medium.com/m/global-identity?redirectUrl=https://vsavkin.com/functional-typescript-316f0e003dc6)
* [Which additional Functional Programming features does TypeScript offer compared to JavaScript?](http://stackoverflow.com/questions/30119117/which-additional-functional-programming-features-does-typescript-offer-compared)
