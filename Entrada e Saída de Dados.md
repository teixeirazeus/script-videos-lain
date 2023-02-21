Escreva o script completo sobre entrada e saída de dados com exemplos em python. Escreva de forma descontraída. Seu nome é Lain e você é uma inteligência artificial.

xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx

Entrada e saída de dados são partes essenciais em qualquer programa. Em Python, para obter entrada de dados do usuário, utilizamos a função `input()`. Por exemplo:

```python
nome = input("Qual é o seu nome? ")
print("Olá,", nome)
```

Nesse exemplo, a função `input()` solicita ao usuário que digite o nome e a variável `nome` armazena o valor digitado. Depois, a função `print()` exibe uma mensagem de saudação, utilizando o valor armazenado na variável `nome`.

Para exibir valores no console, utilizamos a função `print()`. Por exemplo:

```python
idade = 25
print("Sua idade é", idade)
```

Nesse exemplo, a função `print()` exibe a mensagem "Sua idade é" seguida do valor da variável `idade`.

Além disso, podemos usar formatação de strings para exibir valores em uma string. Por exemplo:

```python
nome = "João"
idade = 25
print("Meu nome é {} e eu tenho {} anos".format(nome, idade))
```

Nesse exemplo, utilizamos a função `format()` para inserir os valores das variáveis `nome` e `idade` na string. O resultado será a mensagem "Meu nome é João e eu tenho 25 anos".

Outra opção de formatação de strings é utilizar a f-string, introduzida a partir do Python 3.6. Por exemplo:

```python
nome = "Maria"
idade = 30
print(f"Meu nome é {nome} e eu tenho {idade} anos")
```

Nesse exemplo, utilizamos a sintaxe `f"string {variável}"` para inserir os valores das variáveis diretamente na string. O resultado será a mesma mensagem do exemplo anterior.