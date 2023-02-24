Escreva o script completo sobre expressões aritméticas e lógicas com exemplos em python. Escreva de forma descontraída. Seu nome é Lain e você é uma inteligência artificial.

xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx

As expressões aritméticas e lógicas são fundamentais para qualquer programador, e são utilizadas em diversas situações na criação de algoritmos.

### Expressões Aritméticas

As expressões aritméticas são usadas para realizar cálculos matemáticos. Em Python, temos os seguintes operadores aritméticos:

-   `+`: adição
-   `-`: subtração
-   `*`: multiplicação
-   `/`: divisão
-   `//`: divisão inteira
-   `%`: módulo (resto da divisão)
-   `**`: exponenciação

```python
# Exemplo de expressões aritméticas em Python
a = 10
b = 3

soma = a + b
subtracao = a - b
multiplicacao = a * b
divisao = a / b
divisao_inteira = a // b
resto = a % b
potencia = a ** b

print("Soma:", soma)  # saída: Soma: 13
print("Subtração:", subtracao)  # saída: Subtração: 7
print("Multiplicação:", multiplicacao)  # saída: Multiplicação: 30
print("Divisão:", divisao)  # saída: Divisão: 3.3333333333333335
print("Divisão inteira:", divisao_inteira)  # saída: Divisão inteira: 3
print("Resto:", resto)  # saída: Resto: 1
print("Potência:", potencia)  # saída: Potência: 1000
```

### Expressões Lógicas

Em programação, as expressões lógicas são usadas para fazer comparações entre valores ou variáveis e obter um resultado booleano (verdadeiro ou falso). Em Python, as expressões lógicas são escritas usando os operadores lógicos `and`, `or` e `not`.

Vamos começar com o operador `and`. Ele retorna verdadeiro se ambas as expressões que ele conecta forem verdadeiras. Por exemplo:

```python
x = 5
y = 10
print(x < 10 and y > 5)
```

Nesse exemplo, a expressão `x < 10` é falsa, mas a expressão `y > 5` é verdadeira. Como usamos o operador `and`, o resultado final é falso.

O operador `or`, por outro lado, retorna verdadeiro se pelo menos uma das expressões que ele conecta for verdadeira. Por exemplo:

```python
x = 5
y = 10
print(x < 10 or y < 5)
```

Nesse exemplo, ambas as expressões são falsas, mas como usamos o operador `or`, o resultado final é falso também.

Por fim, temos o operador `not`, que inverte o resultado de uma expressão. Por exemplo:

```python
x = 5
print(not x == 5)
```

Nesse exemplo, a expressão `x == 5` é verdadeira, mas como usamos o operador `not`, o resultado final é falso.

Além dos operadores lógicos, temos também os operadores de comparação, que são usados para comparar valores ou variáveis. Os principais operadores de comparação em Python são:

-   `==`: igual a
-   `!=`: diferente de
-   `>`: maior que
-   `<`: menor que
-   `>=`: maior ou igual a
-   `<=`: menor ou igual a

Por exemplo:

```python
x = 5
y = 10
print(x == y)
print(x != y)
print(x > y)
print(x < y)
print(x >= y)
print(x <= y)
```

Nesse exemplo, o primeiro print vai mostrar falso, já que `x` e `y` são diferentes. O segundo print vai mostrar verdadeiro, já que `x` e `y` são diferentes. Os próximos dois prints vão mostrar falso, já que `x` é menor que `y`. Os dois últimos prints vão mostrar respectivamente falso e verdadeiro.

Espero que esses exemplos tenham ajudado a entender melhor sobre expressões aritméticas e lógicas em Python!