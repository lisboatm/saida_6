# README - Formatação de Frase em Python

## Descrição do Problema

O objetivo deste exercício é criar um programa que manipule e exiba uma frase em diferentes formatos de acordo com especificações de formatação. O programa deve demonstrar o uso de strings e formatação de saída no Python.

## Especificações

1. Crie uma variável para armazenar a frase "AMO FAZER EXERCICIO NO URI".
2. Exiba a frase em diferentes formatos utilizando as diretrizes especificadas.

## Entrada

Não há entrada para este programa.

## Saída

O programa deve gerar a seguinte saída, com a formatação correta:

```
<AMO FAZER EXERCICIO NO URI>
<    AMO FAZER EXERCICIO NO URI>
<AMO FAZER EXERCICIO >
<AMO FAZER EXERCICIO NO URI    >
<AMO FAZER EXERCICIO NO URI>
<          AMO FAZER EXERCICIO >
<AMO FAZER EXERCICIO           >
```

## Formatos de Saída

As seguintes formatações devem ser aplicadas à string:

1. `<valor>`: Exibe o valor original.
2. `<%30s>`: Exibe o valor alinhado à direita em um campo de 30 caracteres.
3. `<%.20s>`: Exibe os primeiros 20 caracteres.
4. `<%-20s>`: Exibe o valor alinhado à esquerda em um campo de 20 caracteres.
5. `<%-30s>`: Exibe o valor alinhado à esquerda em um campo de 30 caracteres.
6. `<%.30s>`: Exibe os primeiros 30 caracteres (no caso, a string inteira).
7. `<%30.20s>`: Exibe o valor alinhado à direita em um campo de 30 caracteres, limitando a 20 caracteres.
8. `<%-30.20s>`: Exibe o valor alinhado à esquerda em um campo de 30 caracteres, limitando a 20 caracteres.

## Implementação

Aqui está um exemplo de como implementar a solução em Python:

```python
# Armazenando a frase em uma variável
frase = "AMO FAZER EXERCICIO NO URI"

# Exibindo a frase em diferentes formatos
print(f"<{frase}>")
print(f"<{frase:>30}>")
print(f"<{frase:.20}>")
print(f"<{frase:<20}>")
print(f"<{frase:<30}>")
print(f"<{frase:.30}>")
print(f"<{frase:>30.20}>")
print(f"<{frase:<30.20}>")
```

## Considerações Finais

- O programa utiliza a formatação de strings do Python para atender às especificações solicitadas.
- A complexidade do algoritmo é O(1), pois não há iterações ou condições a serem verificadas. Apenas manipulações de string e exibição na saída.

## Autores

Este problema foi elaborado como parte do exercício de programação para prática de manipulação de strings e formatação.
