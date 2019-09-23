# POO
Exercicios em Programação Orientada a Objetos (POO)


# Exercícios de POO

## Bloco – Estruturas de Programação

1- Escreva um programa que carregue dois valores A e B pelo teclado e imprima todos os números ímpares entre A e B. 

2- Escreva um programa que leia o nome e salário atual de um funcionário. O programa deve calcular seu novo salário (segundo a tabela abaixo) e mostrar o nome, o salário atual e o salário reajustado do funcionário: 

Faixa salarial
--------------
acima de | até | Acréscimo 
---------|-----|----------
-- | 150 | 25% 
150 | 300 | 20% 
300 | 600 | 15% 
600	| -- 	|	10% 

* repita o processo acima até que seja digitado FIM no lugar do nome do funcionário; 

* mostrar ao final do programa a soma dos salários atuais, a soma dos salários reajustados e a diferença entre eles. 

3- Escreva um programa que leia um número inteiro e mostre a sua conversão em binário. 

4- Os números de Fibonacci formam uma sequência em que cada número é igual à soma dos dois anteriores. Os dois primeiros números são, por definição igual a 1, segundo o exemplo: Ex: 1 1 2 3 5 8 13 ... 

* Escreva um programa que carregue um carregue um número inteiro pelo teclado e indique se ele faz parte da sequência de Fibonacci. 

5- Um banco realiza empréstimos nas seguintes condições:
são tomados “P” reais emprestados;

*	“A” reais serão pagos cada mês até que o empréstimo seja quitado;

* parte do pagamento mensal serão juros, calculados como "i" por cento do saldo corrente;
*	o restante será aplicado no pagamento da dívida. 

* Escreva um programa que leia estes três valores: P, A, i e determine: 

  *	Para cada mês: 

    * valor em dinheiro dos juros pagos; 

    * valor em dinheiro aplicada no pagamento da dívida; 

    * valor acumulado de juros já pagos;

    * valor ainda por pagar do empréstimo no fim de cada mês;
  * No final do programa: 
    *	e) número de meses necessários para pagar o empréstimo; 
    *	f) quantidade da última prestação. 

6- Escreva um programa que determine se uma cadeia de caracteres é um palíndromo ou não. Um palíndromo é uma cadeia que é igual à sua inversa.

Exemplos: 
---------
ENTRADA             | SAIDA
--------------------|------------------------
ASA = ASA (inverso) | é um PALÍNDROMO 
JOAO <> OAOJ (inverso) | não é um PALÍNDROMO 
343 = 343 (inverso) | é um PALÍNDROMO 

## Bloco – Funções 

7- Escreva um módulo para calcular as raízes de uma equação de 2° grau. O módulo receber as constantes A, B e C da equação como parâmetro e retorna três valores: 2 raízes e um STATUS, seguindo os critérios:

*	se houverem duas raízes retorna status 2; 
*	se houver uma raiz apenas retorna status 1 e um dos parâmetros de raiz igual a 0;
*	se não houverem raízes retorna status 0 e os dois parâmetros de raiz igual a 0. 

8- Escreva um programa que carregue um número inteiro e indique se ele é um número primo, para isto deve ser usado um módulo que recebe como parâmetro o número e retorna verdadeiro se ele for primo e falso caso contrário.
 carregue um valor inteiro N pelo teclado e imprima os N primeiros números primos. 

9- Um observador situado no solo e utilizando um aparelho de levantamento topográfico consegue determinar a distância D e o ângulo A do cume de uma montanha em relação à sua localização (observador). Faça um programa para determinar a altura da montanha em relação ao solo e a sua distância horizontal, dados D e A. As expressões necessárias para a solução do problema são:

DHOR = D.Cos(A) 
ALTURA = RAIZ DE(D²-DHOR²) 

Apesar do Java possuir função co-seno pré-definida, a título de ilustração deve ser feito seu cálculo utilizando-se uma função definida pelo programador. Será utilizada a seguinte série com os 10 primeiros termos:

Cos(A)= A²/2!+A²/4!-A² ² ²/6!

## Bloco – Vetores 

10- Escreva uma função que receba como parâmetro um número inteiro relativo a um mês do ano e retorne uma string com o nome deste mês por extenso. Resolva o problema de suas maneiras:

*	sem um vetor, através de uma estrutura switch/case;
*	com um vetor. 

11- Uma empresa precisa realizar uma estatística do salário de seus funcionários. Para isto precisa de um programa que leia uma lista contendo os salários dos funcionários da empresa, e imprima quantos funcionários ganham salário acima da média. Sabe-se que a empresa possui 50 funcionários.
  Considerando que não há um número fixo de 50 funcionários, o programa pergunta no início quantos funcionários possui a empresa e reliza o restante do processo. 

12- Escreva um programa que leia uma lista contendo o peso de uma série de indivíduos em um vetor de números reais. A lista possui 150 elementos. 
Depois que a lista foi toda inserida o programa deve procurar e imprimir qual a posição no vetor onde está o menor peso. 

13- Escreva uma função que receba como parâmetros dois vetores (vetor 1 e vetor 2) contendo duas listas de nomes que já estão classificadas em ordem alfabética. A função deverá fazer um merge do conteúdo dos dois vetores em um terceiro (vetor resultante retornado pela função) mantendo, porém, a ordem alfabética. Isto pode ser feito da seguinte forma:

*	inicialmente o programa se posiciona no início de ambos os vetores;
*	se o elemento atual do vetor 1 for menor que o elemento atual do vetor 2 ele é transferido para o vetor resultante e o programa se desloca para o próximo elemento do vetor 1 (entenda-se por elemento atual aquele em que o programa está posicionado naquele determinado momento);
*	se o elemento do vetor 2 for menor que o elemento do vetor 1 ele é transferido para o vetor resultante e o programa se desloca para o próximo elemento do vetor 2; 
*	isto irá acontecer até que se chegue ao fim de um dos vetores; neste momento o programa descarrega o restante do vetor que ainda não terminou no vetor resultante e encerra a função.











'Exercícios retirados da Unicamp
MC302 – Programação Orientada a Objetos
Instituto de Computação Universidade Estadual de Campinas

Estruturas de Programação, Funções e Vetores 
André Santanchè 2011'
