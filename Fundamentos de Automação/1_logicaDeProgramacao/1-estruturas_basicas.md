# 📘 Estruturas básicas: variáveis, tipos de dados e operadores

## 1️⃣ Variáveis
São como "caixinhas" na memória do computador onde você guarda informações para usar depois. No JavaScript:

```js
let nome = "Testinho";   // pode mudar depois
const idade = 24;        // não pode mudar (constante) 
var cidade = "Várzea Grande";  // antigo, quase não usado
```

**Passos principais:**
1. **Analisar o problema** → O que precisa ser feito?  
2. **Quebrar em passos** → Qual a sequência de ações?  
3. **Traduzir em código** → Escrever instruções claras que o computador executa.  

**Exemplo prático:**
*"Quero verificar se o usuário pode fazer login."*  
- Passo 1: Usuário informa login e senha.  
- Passo 2: Verificar se estão corretos.  
- Passo 3: Se sim → entrar; Se não → mostrar erro.  

---

## 2️⃣ Tipos de dados

São os diferentes tipos de informações que uma variável pode guardar.
Principais tipos em JavaScript:

- **String (texto)** : "Teste Testando";
- **Number (números)** : 25, 3.14;
- **Boolean (verdadeiro/falso)** : true, false;
- **Array (lista de valores)** : [1, 2, 3], ["QA", "Dev", "PO"];
- **Object (conjunto de chave/valor)** :
```js
let pessoa = { nome: "Testinho", idade: 24 };
```

- **Null**: vazio proposital;
- **Undefined**: ainda não definido.

---

## 3️⃣ Operadores

São símbolos usados para fazer cálculos ou comparações.

- Aritméticos (contas):
```js
let soma = 5 + 2;   // 7
let sub = 5 - 2;    // 3
let mult = 5 * 2;   // 10
let div = 10 / 2;   // 5
let resto = 10 % 3; // 1
```
- Comparação (testa valores):
```js
5 == "5"   // true (só compara valor)
5 === "5"  // false (compara valor + tipo)
5 > 2      // true
5 < 2      // false
```

- Lógicos (combina condições):
```js
true && false // false (E)
true || false // true  (OU)
!true         // false (negação)
```