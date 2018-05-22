# Variáveis, expressões, operações e comandos básicos

Abrir o prompt de comando digitar `python`

Este é o shell do Python

#### Função `print`

```
print('Hello, World')

print(4)
print(4.1)
```
#### Função `type`

```
print(type('Hello, World'))
print(type(3))
print(type(3.14))

print(type('3'))
print(type('3.14'))
```

#### Função `input`
```
input('Ta frio hoje?')
```
O Shell é muito limitado para criar coisas mais complexas, então iremos criar programinhas.
Todo programa python tem que ter extensão `.py`

Vamos começar a declarar as variáveis.
```
a = '3'
b = 3
c = 3.14
tipoa = type(a)
tipob = type(b)
tipoc = type(c)

print(a, tipoa, b, tipob, c, tipoc)
```
### Exemplo 1 - Ta frio em Curitiba?

Escrever um programa que pergunte qual a temperatura em Curitiba, responda e informe qual o tipo de variavel é:

```
temp = input('Qual a temperatura em Curitiba?')
print('A temperatura em Curitiba é', temp,'ºC. \nO tipo da variável é', type(temp))

```
## Algumas manipulações básicas

```
temp1 = int(temp)
temp2 = float(temp)

temp = float(input('Qual a temperatura em Curitiba?'))
print(temp, type(temp))
```








