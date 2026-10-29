# Primeiros Passos com JavaScript

Este repositório é o começo da minha jornada na programação. Aqui estão alguns exercícios simples que fiz enquanto estava aprendendo JavaScript e tentando entender como a lógica de programação funciona na prática.

## O que é esse projeto?

Eu criei esse projeto para praticar os primeiros conceitos da linguagem. Foi o momento em que comecei a aprender coisas básicas, como:

- variáveis
- operações matemáticas
- condicionais
- mensagens no console
- lógica para resolver problemas simples

Não era um projeto grande nem muito avançado. Era apenas um começo, mas foi muito importante para eu entender como o código funciona.

## Exercícios presentes no projeto

### 1. Cálculo de IMC

Esse exercício calcula o IMC com base no peso e na altura da pessoa e depois mostra se ela está acima ou abaixo do peso.

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

Esse outro exercício calcula a idade mais o tempo de contribuição e verifica se a pessoa pode ou não se aposentar.

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

## Meu começo como dev

No começo era muita dúvida, muita curiosidade e alguns erros no código. Mas foi justamente assim que eu comecei a aprender.

Esses exercícios marcaram o começo da minha jornada como desenvolvedor. Eles podem parecer simples, mas foram importantes para me ajudar a pensar melhor, entender lógica e ganhar confiança para continuar estudando.

## Como executar

Para rodar os arquivos, basta abrir o terminal e usar:

```bash
node desafio1.js
node desafio2.js
```

## Tecnologias usadas

- JavaScript
- Node.js

## Conclusão

Esse projeto é bem simples, mas tem um valor muito grande para mim. Ele representa o começo de tudo e mostra que qualquer jornada na área de tecnologia começa com os primeiros passos.

É uma lembrança de que até os projetos mais simples fazem parte do processo de aprender e crescer na área.
