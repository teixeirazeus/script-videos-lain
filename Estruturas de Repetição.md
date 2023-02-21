Escreva o script completo sobre estruturas de repetição com exemplos em python. Escreva de forma descontraída e detalhada. Seu nome é Lain e você é uma inteligência artificial.

xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx

As estruturas de repetição são utilizadas para executar um bloco de código várias vezes de forma automática. Em Python, temos duas estruturas de repetição principais: o `while` e o `for`.

O `while` é utilizado para executar um bloco de código enquanto uma determinada condição for verdadeira. Por exemplo:

```python
contador = 0

while contador < 10:
    print(contador)
    contador += 1
```

Nesse exemplo, a estrutura `while` executa o bloco de código enquanto a variável `contador` for menor que 10. A cada iteração, a função `print()` exibe o valor do contador e a variável `contador` é incrementada em 1.

Já o `for` é utilizado para iterar sobre uma sequência de elementos, como uma lista ou uma string. Por exemplo:

```python
frutas = ["maçã", "banana", "laranja"]

for fruta in frutas:
    print(fruta)
```

Nesse exemplo, a estrutura `for` itera sobre a lista de frutas e, em cada iteração, a variável `fruta` recebe um elemento da lista. A função `print()` exibe o valor da variável `fruta`.

Também é possível utilizar a função `range()` junto com a estrutura `for` para iterar sobre uma sequência numérica. Por exemplo:

```python
for i in range(10):
    print(i)
```

Nesse exemplo, a estrutura `for` itera sobre a sequência numérica de 0 a 9. A cada iteração, a função `print()` exibe o valor da variável `i`.

Além disso, é possível utilizar a palavra-chave `break` para interromper o loop antes do seu término e a palavra-chave `continue` para pular a iteração atual e ir para a próxima. Por exemplo:

```python
for i in range(10):
    if i == 5:
        break
    elif i == 3:
        continue
    else:
        print(i)
```

Nesse exemplo, a estrutura `for` itera sobre a sequência numérica de 0 a 9. Quando a variável `i` é igual a 5, a palavra-chave `break` interrompe o loop. Quando a variável `i` é igual a 3, a palavra-chave `continue` pula a iteração atual. Caso contrário, a função `print()` exibe o valor da variável `i`.