# Primeiros Passos com JavaScript

Este repositório reúne meus primeiros exercícios e desafios em JavaScript, uma etapa inicial da minha jornada como desenvolvedor. A ideia aqui foi praticar lógica de programação, aprender a sintaxe da linguagem e começar a transformar problemas do dia a dia em soluções com código.

## Sobre o projeto

O projeto contém pequenos desafios básicos em JavaScript, focados em cálculos e tomada de decisão. Os exemplos mostram como usar variáveis, condicionais, operadores matemáticos e mensagens no console.

### Desafios incluídos

- Cálculo de IMC
- Verificação de aposentadoria

Esses exercícios são simples, mas extremamente importantes para quem está começando na programação, porque ajudam a entender conceitos fundamentais como:

- Declaração de variáveis
- Operações matemáticas
- Estruturas condicionais (`if` / `else`)
- Interpolação de strings
- Lógica de programação

## Desafio 1: Cálculo de IMC

Neste exercício, o código calcula o Índice de Massa Corporal (IMC) de uma pessoa com base no peso e na altura. Em seguida, ele exibe uma mensagem informando se a pessoa está acima ou abaixo do peso ideal.

Exemplo de lógica:

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

## Desafio 2: Verificação de aposentadoria

Neste segundo exercício, o código calcula a soma da idade e do tempo de contribuição para verificar se a pessoa pode se aposentar. A regra muda conforme o sexo, refletindo a lógica de aposentadoria aplicada no exemplo.

Exemplo de lógica:

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

Este repositório representa o começo da minha caminhada como desenvolvedor. Foi uma fase em que eu estava aprendendo os fundamentos da programação, entendendo como escrever código limpo, descobrir lógica e ganhar confiança para criar soluções simples, porém significativas.

Foi nesse momento que comecei a perceber que a tecnologia vai muito além de escrever comandos: trata-se de resolver problemas, criar algo útil e continuar evoluindo todos os dias.

## Como executar

Para rodar os arquivos JavaScript localmente, basta abrir o terminal na pasta do projeto e executar:

```bash
node desafio1.js
node desafio2.js
```

## Objetivo do projeto

O objetivo principal deste repositório é registrar meus primeiros passos na área de programação e mostrar a evolução de um iniciante em JavaScript. É um projeto simples, mas cheio de valor pessoal e de aprendizado.

## Tecnologias utilizadas

- JavaScript
- Node.js

## Conclusão

Este projeto marca o começo da minha jornada como dev. Ele pode parecer pequeno, mas foi fundamental para desenvolver raciocínio lógico, curiosidade e vontade de continuar aprendendo. É o tipo de base que abre portas para desafios maiores no futuro.

"Todo grande caminho começa com o primeiro passo."