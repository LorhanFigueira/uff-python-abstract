<div align="center">

![Work in Progress IMG](img/workinprogress.png)

# 🐍 Manual de Python

### 📚 Anotações, conceitos e exemplos para consulta rápida!

</div>

## 📌 Sobre

Este repositório foi criado com o intuito de ajudar meus amigos da faculdade a entender, memorizar ou até mesmo se aprofundar em alguns assuntos de Python. Eu provavelmente irei me aprofundar no Python, e pode ser que haja algumas coisas que o professor não tenha passado durante a aula. Porém, quando isso ocorrer, eu irei avisar!

> 💡 A Ideia é manter tudo simples, direto e fácil de encontrar.

## 📖 Conteúdo

- [🐍 Fundamentos](#-fundamentos)
- [🔢 Tipos de Dado](#-tipos-de-dado) ✨ **ATUALIZADO!**
- [➕ Operadores](#-operadores) ✨ **ATUALIZADO!**
- [🔀 Estruturas Condicionais](#-estruturas-condicionais) 
- [🔁 Estruturas de Repetição](#-fundamentos) `NÃO ABORDADO`
- [📦 Listas e Tuplas](#-fundamentos) `NÃO ABORDADO`
- [🧩 Funções](#-funções) ✨ **ATUALIZADO!**
- [📁 Arquivos](#-fundamentos) `NÃO ABORDADO`
- [⚠️ Tratamentos de Erros](#-fundamentos) `NÃO ABORDADO`
- [🧱 Classes e POO](#-fundamentos) `NÃO ABORDADO`

## 🐍 Fundamentos

### 📦 Variáveis

Na Programação em geral tudo começa com algo simples: **uma variável**.

Variáveis são espaços utilizados para armazenar informações que podem ser utilizadas e modificadas ao longo do programa. Essas informações podem ser numeros, textos, valores booleanos e diversos outros tipos de dados.

Em **Python**, podemos criar uma variável simplesmente atribuindo um valor a ela:

```python
nome = "Luiz"
idade = 18
```

Nesse exemplo, o `nome` armazena o texto `"Luiz"`, e `idade` armazena o número `18`.

## 🔢 Tipos de Dado

### 🔤 Tipos

Na programação, uma variável possui um tipo de dado que determina o que ela pode armazenar.


### ❔ Input
A função ```input()``` é utilizada para receber informações fornecidas pelo usuário durante a execução do programa. Ela permite que o programa solicite um dado ao usuário e armazene o valor informado para que possa ser utilizado posteriormente.

```python
x = input('Fale um número: ')

print(x)

# Fale um número: 5
# Saída: 5
```

> Vale ressaltar que toda resposta fornecida pelo ```input()``` será do tipo ```String```. Caso seja necessário convertê-la para outro tipo de dado, consulte o tópico  [⚠️ Tratamentos de Erros](#-fundamentos) `NÃO ABORDADO`.

### 🔠 String (str)

String, ou `texto` na programação é utilizado normalmente para guardar um dado do tipo texto.

```python
texto = "Paralelepípedo"
```

Aqui, a variável chamada texto guarda um dado do tipo `texto`.

> `texto` é tudo que está dentro de aspas duplas (" ")

### 🔡 f-string (f)
As f-strings são utilizadas para facilitar a inserção de variáveis e expressões dentro de textos. Para utilizá-las, basta colocar a letra f antes das aspas e inserir os valores desejados entre {}.

``` python
nome = 'Helena'

print(f'Olá! meu nome é {nome}')
```

### 🔢 Integer (int)

Integer, ou `inteiro` na programação é utilizado normalmente para guardar um dado do tipo número inteiro, ele não guarda dado decimal.

```python
x = 67 # Número sugerido pelo Arthur
```

Aqui, a variável chamada `x` guarda um dado do tipo `inteiro`.

> um lembrete, você não deve colocar aspas duplas quando for querer o número. Se não ele irá virar um `texto` invés de um `inteiro`.

### 🔣 Float (float)

Float, ou `ponto flutuante / número decimal` na programação é utilizado normalmente para guardar um dado do tipo decimal, ele também pode guardar um `inteiro`.

```python
x = 6.7 # Número Decimal sugerido pelo Emanuel
y = 3.14
```

Aqui, a variável chamada `x` e `y` guardam os decimais `6.7` e `3.14`.

> como você pode ter notado aqui invés de usar , você utiliza . para tornar algo `decimal`.

### ☑️ Boolean (bool)

Boolean, ou `booleano` na programação, é um tipo de dado utilizado para representar dois valores possíveis: `True` (verdadeiro) ou `False` (falso).

```python
maior_de_idade = True
menor_de_idade = False
```

Aqui vemos que `maior_de_idade` possui o valor `True`, enquanto `menor_de_idade` possui o valor `False`.

> Para o tipo de dado `Booleano` funcionar corretamente, a primeira letra de `True` e `False` deve ser sempre maiúscula.

## ➕ Operadores

Assim como no Excel, aqui também existem operadores matemáticos. Entretanto, eles são um pouco diferentes daqueles que estamos acostumados a ver no Excel.

### 🟰 Valor ( = )
O símbolo ```=``` é utilizado para atribuir um valor a uma variável.

```python
x = 1
```

Nesse exemplo o valor ```1``` é atribuído à variável ```x```.

### 🟰🟰 Igual ( == )
O operador ```==``` é utilizado para verificar se dois valores são iguais. O resultado dessa comparação será ```True (verdadeiro)``` ou ```False (falso)```.

```python
X = 10
X == 10
``` 

### ➕ Adição ( + )

Ele não é diferente tão diferente quanto no Excel.

```python
x = 10
y = 20
result = x + y
print(result) # Saída: 30
```

ele também pode ser utilizado para juntar textos:

```python
nome = 'Felipe'
mensagem = 'Bem vindo'
resultado = mensagem + ' ' + nome
print(resultado) # Saída: 'Bem vindo Felipe'
```

> Caso tente adicionar um `texto` com um `inteiro` ou `decimal`, o Python retornará um erro. Antes de concatená-los, é necessário converter o `inteiro` ou `decimal` para `texto`. Explico como fazer isso em [⚠️ Tratamentos de Erros](#-fundamentos)!

### ➖ Subtração ( - )

Novamente ele não é tão diferente quanto no Excel.

```python
x = 20
y = 5
result = x - y
print(result) # Saída: 15
```

ele também pode negar o valor de uma variável:

```python
x = -30

print(-x) # Saída: 30
```

O Contrário também funciona.

### ✖️ Multiplicação ( \* )

Ele tem umas funcionalidades a mais que no Excel,
O Padrão:

```python
x = 5
y = 10
result = x * y
print(result) # Saída: 50
```

Repetição de texto:

```python
text = 'AA '
print(text * 3) # Saída: 'AA AA AA '
```

> Ele também faz a mesma coisa com listas, porém eu ainda não expliquei sobre o que é uma lista, caso queira saber, está no tópico [📦 Listas e Tuplas](#-fundamentos) `NÃO ABORDADO`!

### ✖️ Potenciação ( \*\* )

Diferente do Excel que utiliza `^`, aqui utilizamos dois asterísticos ( `**` ).

```python
x = 10
y = 5
result = x ** y
print(result) # Saída: 100000
```

> Tem mais uma utilidade os dois asterísticos, porém irei apresenta-lá no tópico [🧩 Funções](#-fundamentos).

### ➗ Divisão ( / )

Não é tão diferente quanto no Excel:

```python
x = 10
y = 2
result = x / y
print(result) # Saída: 5
```

### ➗ Módulo ( % )

O módulo aqui funciona de forma um pouco diferente do Excel. No Excel, ele já é uma função pronta; aqui, você utiliza apenas o operador `%`:

```python
dividendo = 10
divisor = 3
result = dividendo % divisor
print(result) # Saída: 1
```

### ➗ Quociente ( // )

O quociente aqui funciona de uma forma um pouco diferente do Excel também. No Excel, ele já é uma função pronta; aqui, você utiliza apenas o operador `//`.

```python
dividendo = 10
divisor = 3
result = dividendo // divisor
print(result) # Saída: 3
```

## 🔀 Estruturas Condicionais

Uma estrutura condicional é, basicamente, uma forma de verificar se uma determinada condição é `verdadeira` ou `falsa`, utilizando estruturas como `if` e `else`.

Ela pode funcionar de diferentes maneiras, dependendo da lógica que você precisa implementar.

### `if`

```python
idade = 18

if idade >= 10:
    print('Vocẽ é maior de idade.')
```

> **_Importante:_** lembre-se de que o código dentro de um `if`, `elif` ou `else` precisa estar indentado (com espaçamento à frente). Caso contrário, o Python retornará um erro.

### `if` + `else`

```python
idade = 18

if idade >= 10:
    print('Você é maior de idade.')
else:
    print('Você é menor de idade.')

# Saída: 'Você é maior de idade.'
```

### `if` + `elif` + `else`

```python
nota = 8

if idade >= 9:
    print('Excelente')
elif nota >= 6:
    print('Aprovado')
else:
    print('Reprovado')

# Saída: 'Aprovado'
```

> o `elif` serve para verificar várias possibilidades, em vez de apenas uma.

### Várias Condições

```python
idade = 18
tem_ingresso = True

if idade >= 18 and tem_ingresso:
    print('Entrada permitida')
else:
    print('Entrada negada')

# Saída: 'Entrada permitida'
```

> No Python, existem operadores lógicos como `and` (e), `or` (ou) e `not` (não), semelhantes aos utilizados no Excel.

### Condição dentro de outra condição

```python
idade = 20

if idade >= 18:
    if idade >= 60:
        print('Idoso')
    else:
        print('Adulto')
else:
    print('Menor de idade')

# Saída: 'Adulto'
```

## 🧩 Funções
Diferentemente do Excel, em que as funções já são pré-escritas, aqui, o próprio usuário escreve tudo aquilo de que irá precisar, não ficando tão limitado quanto no Excel.
```python
def add(x, y):
    result = x + y
    return result

print(add(1, 2)) # Saída: 3
```
Vou explicar por partes aqui:

```def```, ou “definir”, é utilizado para informar ao Python que estamos criando uma nova função. Ao colocarmos parênteses ao lado do nome da função, podemos definir parâmetros, que são valores recebidos pela função e que podem ser utilizados em seu interior.

No exemplo acima, foram definidos os parâmetros ```x``` e ```y```, indicando que a função pode receber dois valores. É importante ressaltar que a ordem dos parâmetros deve ser respeitada, pois cada valor recebido será associado ao parâmetro correspondente à sua posição. Por exemplo, se o primeiro valor for destinado ao parâmetro ```x``` e o segundo ao ```y```, inverter essa ordem fará com que os valores sejam atribuídos de maneira diferente, podendo alterar o resultado da função.

O ```return``` serve para retornar uma informação ou valor da função, como mencionado anteriormente, em que a função ```add``` retorna o valor ```3``` como saída.
> Ao executar um ```return```, a função é encerrada naquele momento. Portanto, qualquer código escrito após o ```return``` não será executado.


Também é possível informar os valores dos parâmetros utilizando seus respectivos nomes. Dessa forma, não é necessário seguir a ordem em que os parâmetros foram definidos na função.

```python
def divide(x, y):
    result = x / y
    return result

print(divide(y = 5, x = 3))
```

Neste exemplo, definimos que o parâmetro ```y``` receberá o valor ```5```, enquanto o parâmetro ```x``` receberá o valor ```3```. Mesmo que ```y``` tenha sido informado antes de ```x```, o Python consegue identificar corretamente cada valor por meio do nome do parâmetro.

### Função sem return
Funções que não possuem ```return``` são bastante comuns, pois, normalmente, elas contêm um ```print()``` para exibir uma mensagem diretamente na tela, sem a necessidade de retornar esse valor para fora da função.
```python
def gender(x):
    if x == 'M' or x == 'm':
        print('Masculino')
    elif x == 'F' or x == 'f':
        print('Feminino')
    else:
        print('Indefinido')

gender('M') # Saída: Masculino
gender('F') # Saída: Feminino
gender('X') # Saída: Indefinido
```

###  Função sem parâmetros
Como o próprio nome sugere, uma função sem parâmetros é uma função que não recebe nenhum valor no momento em que é chamada. Isso significa que ela executará as instruções definidas em seu interior sem depender de informações fornecidas externamente.

```python
def latir():
    print('au au au au au au au au au auuuuuuuuuuuuuuu')

latir() # Saída: 'au au au au au au au au au auuuuuuuuuuuuuuu'
```
Nesse exemplo, a função **```latir()```** não precisa receber nenhum parâmetro para funcionar> Sempre que ela for chamada, executará as instruções que estão dentro dela.

### Retorno armazenado em variável
É possível armazenar o valor retornado por uma função em uma variável. Dessa forma, podemos utilizar esse resultado posteriormente em outras partes do programa.
```python
resultado = add(1, 5)
print(resultado) # Saída: 6
``` 

### Parâmetros com valor padrão
É possível que o usuário do código esqueça de fornecer um parâmetro ao chamar uma função. Caso isso aconteça, você, como criador(a) do código, pode definir um valor padrão para esse parâmetro. Dessa forma, se nenhum valor for informado, o Python utilizará automaticamente o valor definido como padrão.
```python
def add(x=1,y=1):
    result = x + y
    return result

print(add()) # Saída: 2
```

### Por que utilizar funções?
Funções permitem organizar um conjunto de instruções em um bloco reutilizável. Dessa forma, podemos executar o mesmo conjunto de operações várias vezes sem precisar escrever o mesmo código novamente. Além disso, por meio dos parâmetros, uma mesma função pode trabalhar com diferentes valores de entrada.

```python
def add(x, y):
    return x + y

print(add(2, 3)) # Saída: 5
print(add(10, 20)) # Saída: 30
print(add(50, 100)) # Saída: 150
```