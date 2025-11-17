# 🚀 100 Exercícios em JavaScript

Bem-vindo(a)! Este repositório contém **200 exercícios práticos de JavaScript** para te ajudar a aprender, praticar e dominar a linguagem. Cada exercício aborda conceitos importantes, do básico ao avançado, com foco em capacidade de resolução, raciocínio lógico e boas práticas.

---



## ✅ Como usar

1. **Clonar o repositório**

```bash
git clone <url-do-repositorio>
cd <repositorio>/TodasAtividades
```

2. **Executar um exercício com Node.js**

```bash
node Atividade01.js
```

> Requisito: Node.js instalado (recomenda-se v14+).

3. **Executar vários exercícios**

Para rodar todos em sequência (apenas para fins de execução rápida), crie um script ou use um `for` no terminal:

```bash
for f in Atividade*.js; do node "$f"; done
```

> Atenção: alguns exercícios podem pedir entrada do usuário ou depender de variáveis; verifique cada arquivo antes de executar em lote.

---

## 🧭 Organização por temas (exemplos)

* **1–20**: Variáveis, operadores, condicionais básicas
* **21–50**: Loops (`for`, `while`, `do-while`), manipulação básica de strings
* **51–100**: Funções, recursão, arrays simples


## 🛠️ Formato dos arquivos / Boas práticas de código

* **ES6+**: use `const` e `let` ao invés de `var`.
* **Funções**: prefira funções claras e reutilizáveis. Comente trechos importantes.
* **Entrada/saída**: quando um exercício requer entrada, favor usar `prompt-sync` (para execução local) ou parâmetros fixos no arquivo para testes automáticos.
* **Nomes**: siga `camelCase` para variáveis e funções.

Exemplo de cabeçalho sugerido para cada atividade:

```js
// Atividade01.js
// Título: Somar dois números
// Descrição: Recebe dois números e imprime a soma.
// Execução: node Atividade01.js

const a = 10;
const b = 5;
console.log(`Soma: ${a + b}`);
```

---

## 🧪 Testes e validação

* Para validação manual, execute com `node` e confira a saída no console.
* Se desejar, podemos adicionar um conjunto de testes usando **Jest** ou **Mocha** para automatizar a verificação das soluções.

---

## ✍️ Como contribuir

1. Faça um fork do repositório.
2. Crie uma branch com a feature: `git checkout -b feat/exercicio-05`.
3. Implemente a solução ou melhorias.
4. Abra um pull request com uma descrição clara.

Sugestões de contribuição:

* Adicionar comentários explicativos nas soluções.
* Fornecer versões alternativas (iterativas/recursivas).
* Criar testes automatizados para cada exercício.

---

## 📚 Recursos e referências

* MDN Web Docs — JavaScript
* Node.js Docs
* Livro sugerido: "You Don't Know JS" (Kyle Simpson)

---

## 🧾 Licença

Este material é fornecido para aprendizado. Se desejar, adicione uma licença (por exemplo, MIT) ao repositório.

---



