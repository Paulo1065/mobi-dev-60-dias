# Projeto 60 Dias — Aula 02

**Data:** 16/09/2026  
**Foco:** Introdução ao JavaScript

## Objetivo da aula

Iniciar JavaScript do zero, entendendo primeiro o papel da linguagem e depois os conceitos fundamentais, sem pular etapas.

## Base

- HTML = estrutura
- CSS = aparência
- JavaScript = comportamento e interatividade

## Conteúdos estudados

### 1. Console

```javascript
console.log("Olá, Mobi!");
```

Usado para exibir informações no console do navegador.

### 2. Variáveis com `let`

```javascript
let nome = "Mobi Systems";
nome = "Mobi Cell";
```

`let` permite reatribuir o valor depois.

### 3. Constantes com `const`

```javascript
const empresa = "Mobi Systems";
```

`const` é usado quando a referência não deve ser reatribuída.

### 4. Tipos de valores

**String:**
```javascript
let nome = "Mobi Systems";
```

**Number:**
```javascript
let preco = 150;
```

**Boolean:**
```javascript
let ativo = true;
let pagamentoAprovado = false;
```

### 5. Operadores matemáticos

- `+` soma
- `-` subtração
- `*` multiplicação
- `/` divisão

Exemplo:

```javascript
let total = 10 * 5;
```

### 6. Comparações

- `>` maior que
- `<` menor que
- `>=` maior ou igual
- `<=` menor ou igual
- `===` exatamente igual
- `!==` diferente

### 7. Condicionais

```javascript
let saldo = 200;

if (saldo >= 100) {
    console.log("Compra aprovada");
} else {
    console.log("Saldo insuficiente");
}
```

Também foi apresentado `else if` para decisões com mais de duas possibilidades.

### 8. Funções

```javascript
function saudacao() {
    console.log("Olá, Mobi!");
}

saudacao();
```

### 9. Parâmetros

```javascript
function saudacao(nome) {
    console.log("Olá, " + nome);
}

saudacao("Mobi");
```

### 10. `return`

```javascript
function somar(a, b) {
    return a + b;
}

let resultado = somar(10, 5);
```

`return` devolve um valor para ser usado posteriormente.

### 11. Primeiro contato com JavaScript no HTML

```html
<button onclick="saudacao()">Clique aqui</button>
```

```javascript
function saudacao() {
    alert("Olá, Mobi!");
}
```

Foi introduzido também o conceito de localizar elementos pelo `id` com `document.getElementById()`, mas a aula foi pausada nesse ponto para registro no GitHub.

## Resultado

Primeira aula de JavaScript concluída com compreensão inicial de variáveis, tipos, operadores, condições, funções e interação com HTML.

**Status:** ✅ Aula concluída / próxima aula continua em DOM e `getElementById`
