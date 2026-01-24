# Desafio: Classificador de Nível de Herói

Esse projeto foi desenvolvido para aplicar conceitos de estruturas de repetição e condicionais em JavaScript.

## Objetivo
Classificar automaticamente uma lista de heróis baseando-se em sua experiência (XP), utilizando um fluxo de controle otimizado.

## Lógica Aplicada

### 1. Estrutura de Dados
Utilizei um **Array de Objetos** para armazenar os heróis. Isso permite que cada herói tenha suas próprias propriedades (`nome` e `xp`) de forma organizada.

### 2. Laço de Repetição (`for`)
O laço percorre a lista do primeiro ao último elemento. A cada iteração:
* A variável `i` atua como o índice (posição) atual.
* `herois[i]` acessa o objeto específico daquela posição.



### 3. Estrutura Condicional
Utilizei o encadeamento `if / else if / else`. 
* **Vantagem:** O código é mais eficiente, pois assim que uma condição é verdadeira, ele pula as demais verificações.

---

## Regras de Classificação

Se XP for menor do que 1.000 = Ferro
Se XP for entre 1.001 e 2.000 = Bronze
Se XP for entre 2.001 e 5.000 = Prata
Se XP for entre 5.001 e 7.000 = Ouro
Se XP for entre 7.001 e 8.000 = Platina
Se XP for entre 8.001 e 9.000 = Ascendente
Se XP for entre 9.001 e 10.000= Imortal
Se XP for maior ou igual a 10.001 = Radiante

## Resultado esperado no console

O Herói de nome Mario está no nível de Ferro
O Herói de nome Link está no nível de Bronze
O Herói de nome Zelda está no nível de Prata
O Herói de nome Luigi está no nível de Radiante
