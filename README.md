# Christian Sameul Sampaio - 2° período - 24118253 
# Tive que zipar, pois não estava conseguindo enviar para o Git. Ele estava criando esse .gitattributes e o .gitignore.
# Mas já tem tudo que precisa na pasta zipada: ProjetoQuestoesCSharp 
# Documentação do Projeto: Questões de Programação em C#
## Explicação do Projeto

Este projeto consiste em uma aplicação de console em C# que oferece um menu interativo com 101 questões de programação. O usuário pode selecionar uma questão digitando o número correspondente. Cada questão é implementada em um método separado, facilitando a organização e a manutenção do código. Ao concluir uma questão, o usuário é levado de volta ao menu inicial, onde pode escolher outra questão ou sair do programa.

### Funcionalidades Principais

- Um menu inicial que permite ao usuário escolher entre diferentes questões.
- Cada questão é implementada como um método separado, chamado com base na escolha do usuário.
- O programa continua em execução até que o usuário decida sair.

## Instruções para Executar o Código

Para executar o projeto, siga as instruções abaixo:

1. **Instalar o .NET SDK**:
   - Certifique-se de ter o .NET SDK instalado no seu computador. Você pode baixá-lo do site oficial da [.NET](https://dotnet.microsoft.com/download).

2. **Criar um Novo Projeto**:
   - Abra o terminal (ou prompt de comando) e crie um novo projeto de console com o seguinte comando:
     ```
     dotnet new console -n QuestõesCSharp
     ```
   - Navegue até o diretório do projeto:
     ```
     cd QuestõesCSharp
     ```

3. **Substituir o Código**:
   - Abra o arquivo `Program.cs` no seu editor de texto ou IDE de sua preferência.
   - Substitua o conteúdo do arquivo pelo código fornecido anteriormente.

4. **Compilar o Projeto**:
   - No terminal, compile o projeto com o seguinte comando:
     ```
     dotnet build
     ```

5. **Executar o Programa**:
   - Após a compilação bem-sucedida, execute o programa com o seguinte comando:
     ```
     dotnet run
     ```

6. **Interagir com o Menu**:
   - Siga as instruções exibidas no console para escolher e executar as questões.
   - 0 para sair

## Questões Implementadas

Aqui está a lista das questões de programação implementadas:

1. Crie uma classe Produto com propriedades Nome e Preco.
2. Instancie um objeto da classe Produto e exiba seus valores.
3. Crie um método que soma dois números inteiros e exibe o resultado.
4. Escreva uma função que verifica se um número é par ou ímpar.
5. Implemente um método que converte um valor em metros para centímetros.
6. Crie um programa que recebe a idade e verifica se a pessoa é maior de idade.
7. Escreva um método que calcula a área de um círculo com base no raio fornecido.
8. Crie um programa que exibe a tabuada de um número fornecido.
9. Desenvolva um método que soma todos os números de 1 a N.
10. Implemente uma função que converte temperatura de Celsius para Fahrenheit.
11. Crie uma função que verifica se uma string é vazia ou nula.
12. Crie uma função que exibe todos os números pares entre 1 e 50.
13. Implemente uma função que recebe três números e retorna o maior deles.
14. Crie um programa que inverte uma string.
15. Desenvolva uma função que verifica se uma pessoa pode votar, dado o ano de nascimento.
16. Crie uma função que verifica se um número é positivo ou negativo.
17. Implemente um programa que calcula a média de três notas e exibe a situação (Aprovado/Reprovado).
18. Escreva uma função que conta quantas letras 'a' existem em uma string.
19. Crie um programa que imprime números de 1 a 10 em ordem decrescente.
20. Implemente uma função que calcula a soma dos quadrados dos números de 1 a N.
21. Crie uma função que recebe o nome e a idade de uma pessoa e exibe uma mensagem de boas-vindas.
22. Escreva um programa que recebe um número e exibe seu dobro e triplo.
23. Crie uma função que retorna o último caractere de uma string fornecida.
24. Implemente uma função que converte horas em segundos.
25. Crie uma função que verifica se um número é divisível por 3 e por 5.
26. Crie uma função que ordena três números fornecidos.
27. Desenvolva um programa que calcula o fatorial de um número.
28. Crie uma classe Aluno com propriedades Nome e Nota. Implemente um método para exibir esses valores.
29. Implemente um método que calcula a média de uma lista de números.
30. Crie um programa que verifica se uma palavra é um palíndromo.
31. Implemente uma função que encontra o menor número em um array.
32. Crie uma função que multiplica todos os elementos de um array por um valor fornecido.
33. Desenvolva uma função que retorna a soma dos números ímpares em um array.
34. Crie uma classe Carro com propriedades Marca e Ano.
35. Implemente um método para verificar se um ano é bissexto.
36. Crie uma função que exibe os 10 primeiros números da sequência de Fibonacci.
37. Desenvolva um programa que recebe uma string e substitui todos os espaços por '_'.
38. Crie uma função que retorna o índice do maior elemento de um array.
39. Implemente uma função que calcula o MDC (Máximo Divisor Comum) entre dois números.
40. Desenvolva uma função que retorna o número de vogais em uma string.
41. Crie uma função que converte um número decimal para binário.
42. Implemente uma função que recebe um número e exibe sua representação em palavras.
43. Crie um programa que simula o lançamento de um dado 100 vezes e exibe a frequência de cada valor.
44. Desenvolva uma função que calcula o IMC e determina a categoria (baixo peso, normal, etc.).
45. Crie uma função que encontra o segundo maior número em um array.
46. Implemente um programa que inverte os elementos de um array.
47. Crie uma função que soma duas matrizes 2x2.
48. Desenvolva uma função que recebe uma data e exibe o dia da semana correspondente.
49. Crie um programa que verifica se uma string contém apenas letras e números.
50. Implemente uma função que calcula o valor de uma potência sem usar Math.Pow().
51. Crie uma função que verifica se uma matriz é simétrica.
52. Desenvolva um programa que ordena uma lista de nomes em ordem alfabética.
53. Crie uma função que encontra o elemento mais frequente em um array.
54. Implemente uma função que calcula o valor absoluto de um número sem usar Math.Abs().
55. Crie um programa que implementa o algoritmo de busca linear.
56. Desenvolva um programa que simula um cronômetro simples (usando Thread.Sleep).
57. Implemente uma função que calcula o número de palavras em uma string.
58. Crie uma classe Pessoa com método Falar() que exibe uma mensagem personalizada.
59. Crie uma função que retorna a interseção entre dois arrays.
60. Desenvolva uma função que converte uma string para maiúsculas alternadas e minúsculas.
61. Implemente uma função que retorna o número de caracteres únicos em uma string.
62. Crie um programa que exibe os números primos até um valor fornecido.
63. Desenvolva uma função que verifica se um número é perfeito.
64. Crie uma função que exibe os divisores de um número.
65. Implemente um método para calcular a transposta de uma matriz.
66. Crie um programa que exibe o horário atual continuamente (até ser encerrado).
67. Desenvolva uma função que simula uma calculadora simples (+, -, *, /).
68. Crie um programa que converte valores monetários para extenso.
69. Implemente um método que calcula a média ponderada de notas.
70. Crie um programa que simula um caixa eletrônico para saques.
71. Desenvolva uma função que verifica se dois arrays são iguais (mesmos elementos e mesma ordem).
72. Implemente uma função que gera uma senha aleatória com letras e números.
73. Crie um programa que gera uma tabela de multiplicação.
74. Desenvolva uma função que calcula a área de um triângulo com base em três lados.
75. Crie uma função que gera números aleatórios únicos entre 1 e N.
76. Crie um jogo de "Adivinhe o Número" entre 1 e 100, dando dicas se o valor é maior ou menor.
77. Implemente uma função que verifica se dois arrays possuem os mesmos elementos, independentemente da ordem.
78. Crie uma função que simula uma fila de atendimento (FIFO) usando List<T>.
79. Desenvolva um jogo simples de "Pedra, Papel e Tesoura" que joga contra o computador.
80. Crie um programa que calcula a soma dos dígitos de um número fornecido pelo usuário.
81. Implemente uma função que encontra e exibe os números pares em uma lista.
82. Desenvolva um programa que lê valores do usuário e exibe a média e o maior valor informado.
83. Crie um programa que armazena 10 nomes e os exibe em ordem inversa.
84. Implemente uma função que retorna o quadrado de um número sem usar o operador de multiplicação.
85. Crie um programa que exibe a contagem regressiva de 10 a 0.
86. Desenvolva um jogo simples de "Forca" onde o usuário tenta adivinhar uma palavra em até 5 tentativas.
87. Implemente uma função que converte um valor em reais para dólares, considerando uma taxa de câmbio fixa.
88. Crie um programa que gera um número aleatório entre 1 e 100 e permite que o usuário adivinhe.
89. Desenvolva um programa que exibe os 10 primeiros números da sequência de Fibonacci.
90. Implemente uma função que calcula a soma dos elementos de uma matriz.
91. Crie um programa que simula um jogo de adivinhação de palavras, onde o usuário tenta descobrir uma palavra secreta.
92. Desenvolva um programa que calcula a média dos números em um array de inteiros.
93. Implemente uma função que retorna uma lista de números primos até um valor fornecido.
94. Crie um programa que gera uma lista de números aleatórios e exibe o maior e o menor.
95. Desenvolva uma função que inverte os elementos de um array usando recursão.
96. Crie um programa que simula um jogo de trivia com perguntas e respostas.
97. Implemente uma função que calcula o total de um pedido com base em itens e preços.
98. Crie um programa que permite ao usuário registrar despesas e exibir um relatório.
99. Desenvolva uma função que ordena uma lista de números usando o algoritmo Bubble Sort.
100. Implemente um método que calcula o somatório de uma série de números em um intervalo definido.
101. Crie um jogo simples de "Forca" onde o usuário tenta adivinhar uma palavra em até 5 tentativas.
