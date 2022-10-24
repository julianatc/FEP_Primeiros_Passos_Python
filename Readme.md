# Exercíos de Fixaçāo (Degrau 1) - Primeiros Passos na linguagem Python

Resolvido os exercícios de revisāo/fixaçāo, referente aos seguintes tópicos:
- Funçāo print()
- Funçāo input()
- Operadores Aritméticos 
- Operadores relacionais e lógicos 
- f-strings
- Métodos de manipulaçāo de strings 
- Técnica de fatiamento (Slicing)
- Estruturas de dados (listas, dicionários, tuplas, conjuntos)
- Estruturas de repetiçāo e condicionais (for, while, if)
- Funções

# BUSINESS CASE 

Incluído resoluçāo do problema de Business Case descrito abaixo: 

Você é um personal trainer e trabalha em uma pequena academia.
Toda vez que chega um novo aluno(a) , precisa criar uma ficha com as seguintes informações: Nome, idade, peso, altura, IMC (indice de massa corporal). Você utiliza o Word para criar as fichas. 
Você começou a estudar Python e quer trabalhar de uma forma mais inteligente, com isso vai criar um pequeno script para gerar um PDF com todos os dados e o IMC calculado de forma automática.


- Modificações/melhorias que incluí na soluçāo para praticar (ir além):
1 - Criaçāo de FUNCĀO PYTHON 
  - Realizei o cálculo do IMC por meio de funçāo que recebe os parametros PESO e ALTURA
  - Inclui validações para verificar a classificaçāo do IMC (normal, sobrepeso, obesidade, obesidade grave, abaixo do peso) conforme referencias encontrada na Internet
2 - Alteraçāo no template PDF
  - Alterei o template PDF para mostrar mensagem em um quadro VERDE apenas se a classificaçāo for normal e para as demais classificaçōes retornar na cor VERMELHO. Também alterado para mostrar a descriçāo da classificaçāo independentemente da mensagem.
3 - Alteraçāo no layout do nome do arquivo PDF
  - Incluí input para solicitar o CPF do aluno(a) para que o valor seja concatenado no nome do arquivo PDF, 
  evitando assim que o script sobreponha o arquivo a cada teste de diferentes alunos.
