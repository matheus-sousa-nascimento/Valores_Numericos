# Projeto - Calculadora Simples

Este projeto em Java realiza operações aritméticas simples entre dois números inteiros. O programa solicita ao usuário dois números e uma operação matemática (adição, subtração, multiplicação ou divisão). Dependendo da operação selecionada, o programa exibe o resultado.

## Funcionalidade

O programa solicita:
1. O primeiro número.
2. O segundo número.
3. A operação aritmética desejada: soma (`+`), subtração (`-`), multiplicação (`*`) ou divisão (`/`).

O programa então realiza a operação aritmética selecionada e exibe o resultado. Se uma operação inválida for fornecida, o programa exibe uma mensagem de erro.

### Exemplo:

- Se o usuário digitar:
  - Primeiro número: `10`
  - Segundo número: `5`
  - Operação: `+`
  - O resultado será: `15`.

- Se o usuário digitar uma operação inválida (como `^`), o programa exibirá: `ERRO!!!`.

## Como Funciona

1. O programa solicita o primeiro número, o segundo número e a operação.
2. Com base na operação fornecida:
   - Soma (`+`): Soma os dois números.
   - Subtração (`-`): Subtrai o segundo número do primeiro.
   - Multiplicação (`*`): Multiplica os dois números.
   - Divisão (`/`): Divide o primeiro número pelo segundo (com cuidado para não gerar erro de divisão por zero).
3. O programa exibe o resultado da operação ou uma mensagem de erro, se a operação for inválida.

 ```bash
Digite um valor: 10
Digite um valor: 5
Digite a operacao aritimetica: +
15
