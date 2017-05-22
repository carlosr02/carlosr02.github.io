# TypeScript
Carlos Romero Bacurau de Brito (carlosr02), 20141011110255
<h2>Resumo</h2>

* Propósito da linguagem: projetada para o desenvolvimento de aplicações de grande porte. Pode ser utilizada para desenvolver aplicações JavaScript para front-end e back-end (Node.js);
* Multiparadigma: scripting, orientada a objetos, estruturada, imperativa, funcional, genérica;
* Data de criação: 2012 por [Anders Hejlsberg](https://pt.wikipedia.org/wiki/Anders_Hejlsberg); e,
* Principal mantenedor: [Microsoft](https://www.microsoft.com/pt-br/).
<h2>Instalação e Uso</h2>

Proceda a uma das opções abaixo para instalar as ferramentas TypeScript:

* Execute o comando a seguir na linha de comando: `npm install -g typescript` ou
* Faça a instalação do plugin para o Visual Studio: [TypeScript for Visual Studio 2015](https://www.microsoft.com/en-us/download/details.aspx?id=48593)

Para compilar, execute o comando a seguir: `tsc [nome_arquivo].ts`
<h2>Sintaxe Básica</h2>
<h3>Variáveis e constantes</h3>

**let** e **const** são dois novos tipos de declaração de variáveis em JavaScript. **let** é semelhante a **var** em alguns aspectos, mas permite que o usuário evite algumas armadilhas recorrentes em JavaScipt. **const** é um acremento de **let** que previne reatribuição de valores a uma variável.
<h4>Declarando com let</h4>

Declarações com **let** são escritas da mesma forma que declarações com **var**. A principal diferença, no entanto, não é a sintaxe, mas a semântica. Propriedades como: block-scoping, sem re-declarations, shadowing permitem que alguns dos bugs provenientes do uso do **var** sejam evitados.

`let hello = "Hello!";`
<h4>Declarando com const</h4>

Declarações com **const** são outra forma de declarar variáveis. Elas são parecidas com declarações com **let**, mas seus valores não podem ser alterados depois de definidos.

`const numLivesForCat = 9;`

<h3>Operadores relacionais e lógicos</h3>
<h4>Operadores relacionais</h4>

Operadores relacionais testam ou definem o tipo de relação entre duas entidades. Estes operadores retornam um valor booleano, i.e., true/false.

Assuma que o valor de A é 10 e de B é 20.

| Operador | Descrição | Exemplo | 
| :---: | :---: | :---: |
| > | maior que | (A > B) é false |
| < | menor que | (A < B) é true |
| >= | maior ou igual que | (A >= B) é false |
| <= | menor ou igual que | (A <= B) é true|
| == | igual | (A == B) é false|
| != | diferente | (A != B) é true|

<h4>Operadores lógicos</h4>

Operadores lógicos são utilizados para combinar duas ou mais condições. Estes operadores também retornam um valor booleano.

Assuma que o valor de A é 10 e de B é 20.

| Operador | Descrição | Exemplo | 
| :---: | :---: | :---: |
| && (E) | o operador retorna true somente se todas as expressões forem verdadeiras | (A > 10 && B > 10) é false |
| \|\| (OU) | o operador retorna true se pelo menos uma expressão for verdadeira | (A > 10 \|\| B > 10) é true |
| ! (NÃO) | o operador retorna o inverso do resultado da expressão | !(A > 10) é true |
