# Primeiros Passos com JavaScript

Esse repositório representa meu começo na programação e meus primeiros exercícios em JavaScript. Quando eu comecei, a ideia era simples: entender a lógica por trás do código, aprender a escrever instruções e perceber que programação não é mágica, é treino, tentativa, erro e evolução.

Aqui estão alguns dos primeiros desafios que eu resolvi enquanto aprendia. Não são projetos gigantes nem soluções super complexas, mas foram fundamentais para eu entender como funciona a base da programação.

## Sobre o projeto

O objetivo principal foi praticar os primeiros conceitos da linguagem JavaScript, como:

- variáveis
- operadores matemáticos
- condicionais (`if` e `else`)
- interpolação de strings
- lógica de programação

## Desafios incluídos

### 1. Cálculo de IMC

Neste exercício, o código calcula o Índice de Massa Corporal (IMC) com base no peso e na altura, e depois mostra se a pessoa está acima ou abaixo do peso ideal.

```javascript
const nome = 'Carlos';
const peso = 80;
const altura = 1.88;

const imc = peso / (altura * altura);

if (imc >= 30) {
  console.log(`${nome} Você esta acima do peso`);
} else {
  console.log(`${nome} Você esta abaixo do peso`);
}
```

### 2. Verificação de aposentadoria

Esse segundo exercício faz uma validação simples de aposentadoria, combinando idade e tempo de contribuição. A lógica foi aplicada com condicionais para verificar se a pessoa pode ou não se aposentar.

```javascript
const nome = 'fabio';
const sexo = 'M';
const idade = 72;
const contribuicao = 23;

const soma = idade + contribuicao;

if (sexo == 'M') {
  if (soma >= 95) {
    console.log(`${nome} voce pode se aposentar`);
  } else {
    console.log(`${nome} Voce nao pode se aposentar`);
  }
}
```

## Meu início na carreira de desenvolvimento

Eu não comecei sabendo fazer tudo. No começo era muita dúvida, muita curiosidade e alguns erros no código. Mas foi justamente assim que eu comecei a aprender.

Esses exercícios representam o momento em que eu estava começando a entender como um programa funciona, como a lógica se organiza e como pequenas decisões no código podem mudar completamente o resultado.

Foi nessa fase que eu percebi que programação não é só escrever comandos; é resolver problemas, testar ideias e continuar aprendendo sempre.

## Como executar

Para rodar os arquivos JavaScript localmente, basta abrir o terminal e executar:

```bash
node desafio1.js
node desafio2.js
```

## Tecnologias utilizadas

- JavaScript
- Node.js

## Conclusão

Este projeto é bem simples, mas tem um valor enorme para mim. Ele marca o começo da minha jornada como desenvolvedor e mostra a partir de onde tudo começou: com vontade de aprender, curiosidade e pequenos passos.

É uma lembrança de que toda grande evolução começa com os conceitos mais básicos.
