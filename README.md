# Calculadora-Python
 Projeto de um calculadora desenvolvida em python

Este projeto consiste em uma calculadora desenvolvida em Python. O programa permite que o usuário informe dois números e escolha uma operação matemática entre soma, subtração, multiplicação e divisão.

## Arquivos do projeto
calculadora.py - contém o código principal da calculadora.

calculadora.sh - arquivo executável utilizado para iniciar a calculadora.


## Como executar o arquivo .sh

Primeiramente, é necessário dar permissão de execução ao arquivo: chmod +x calculadora.sh

Depois, execute o arquivo com: ./calculadora.sh

O arquivo calculadora.sh executará o programa calculadora.py utilizando o Python 3.

## Como executar o código Python

Também é possível executar diretamente o arquivo Python utilizando: python3 calculadora.py

Após iniciar o programa, o usuário deverá informar dois números e escolher uma das operações disponíveis: + para soma; - para subtração; * para multiplicação e / para divisão.

## Explicação do código Python

Programa utiliza um laço while True para permitir que a calculadora continue funcionando enquanto o usuário não escolher encerrá-la.

Primeiramente, o programa solicita dois números ao usuário utilizando input(). A função float() é utilizada para transformar os valores informados em números que podem possuir casas decimais.

Em seguida, o programa solicita qual operação matemática deverá ser realizada.

A estrutura if, elif e else verifica a operação escolhida:

Se o usuário escolher +, os dois números são somados.
Se escolher -, é realizada uma subtração.
Se escolher *, é realizada uma multiplicação.
Se escolher /, é realizada uma divisão.

Na divisão, o programa verifica se o segundo número é igual a zero. Caso seja, uma mensagem informa que não é possível dividir por zero.

Caso o usuário informe uma operação que não está disponível, o programa apresenta uma mensagem informando que a operação é inválida.

Por fim, o programa pergunta se o usuário deseja parar. Se a resposta for sim, o comando break encerra o laço e finaliza a calculadora.
