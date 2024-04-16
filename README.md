# Notas-e-Conceito

# Calculadora de Notas e Conceitos

Este programa em C permite calcular o conceito de um aluno com base em três notas fornecidas.

## Requisitos

Para compilar e executar este programa, é necessário um compilador C instalado no seu sistema. Você pode usar o GCC ou outro compilador de sua preferência.

## Como Usar

1. Clone este repositório ou baixe o arquivo `codigo.c`.
2. Abra um terminal e navegue até o diretório onde o arquivo `codigo.c` está localizado.
3. Compile o código-fonte usando o seguinte comando:

    ```
    gcc codigo.c -o calculadora_notas
    ```

4. Execute o programa recém-compilado:

    ```
    ./calculadora_notas
    ```

5. Siga as instruções exibidas no console para inserir as três notas do aluno.
6. O programa calculará a média das notas e atribuirá um conceito com base na média, exibindo o resultado.

## Exemplo

```
Digite sua primeira nota:
8
Digite sua segunda nota:
7
Digite sua terceira nota:
9
Sua nota foi: 8 e você recebeu conceito A
```

## Observações

- Este programa solicita ao usuário para inserir três notas.
- Calcula a média das notas e atribui um conceito de acordo com a seguinte escala:
  - A: Média maior ou igual a 9
  - B: Média maior ou igual a 7 e menor que 9
  - C: Média maior ou igual a 6 e menor que 7
  - D: Média maior ou igual a 4 e menor que 6
  - E: Média menor que 4
- O programa repete o processo 10 vezes, permitindo avaliar as notas de múltiplos alunos.
