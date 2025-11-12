## 1️⃣ If / Else
O `if` é usado para executar um bloco de código somente se uma condição for verdadeira. O else é opcional e serve para executar outro bloco caso a condição seja falsa.

Exemplo:
```js
let idade = 18;

if (idade >= 18) {
  console.log("Você é maior de idade");
} else {
  console.log("Você é menor de idade");
}
```

Aqui, se idade for maior ou igual a 18, o if será executado. Se não, o else será executado.

---

## 2️⃣ Switch

O `switch` é usado quando se precisa verificar uma variável em vários casos possíveis, de forma mais organizada que vários `if/else if`.

Exemplo:
```js
let dia = "terça";

switch (dia) {
  case "segunda":
    console.log("Hoje é segunda");
    break;
  case "terça":
    console.log("Hoje é terça");
    break;
  default:
    console.log("Outro dia da semana");
}
```
Cada case representa um valor que a variável pode ter. O default é executado se nenhum dos casos corresponder.