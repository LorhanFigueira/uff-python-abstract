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
- [🔢 Tipos de Dado](#-tipos-de-dado)
- [➕ Operadores](#-operadores) ✨ **ATUALIZADO!**
- [🔀 Estruturas Condicionais](#-estruturas-condicionais) ✨ **ATUALIZADO!**
- [🔁 Estruturas de Repetição](#-fundamentos) `NÃO ABORDADO`
- [📦 Listas e Tuplas](#-fundamentos) `NÃO ABORDADO`
- [🧩 Funções](#-fundamentos)
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
Nesse exemplo, o ```nome``` armazena o texto ```"Luiz"```, e ```idade``` armazena o número ```18```.

## 🔢 Tipos de Dado
### 🔤 Tipos
Na programação, uma variável possui um tipo de dado que determina o que ela pode armazenar.

### 🔠 String (str)
String, ou ```texto``` na programação é utilizado normalmente para guardar um dado do tipo texto.
```python
texto = "Paralelepípedo"
```
Aqui, a variável chamada texto guarda um dado do tipo ```texto```.
> ```texto``` é tudo que está dentro de aspas duplas (" ")

### 🔢 Integer (int)
Integer, ou  ```inteiro``` na programação é utilizado normalmente para guardar um dado do tipo número inteiro, ele não guarda dado decimal.
```python
x = 67 # Número sugerido pelo Arthur 
```
Aqui, a variável chamada ```x``` guarda um dado do tipo ```inteiro```.
> um lembrete, você não deve colocar aspas duplas quando for querer o número. Se não ele irá virar um ```texto``` invés de um ```inteiro```.

### 🔣 Float (float)
Float, ou ```ponto flutuante / número decimal``` na programação é utilizado normalmente para guardar um dado do tipo decimal, ele também pode guardar um ```inteiro```.
```python
x = 6.7 # Número Decimal sugerido pelo Emanuel
y = 3.14
```
Aqui, a variável chamada ```x``` e ```y``` guardam os decimais ```6.7``` e ```3.14```.
> como você pode ter notado aqui invés de usar , você utiliza . para tornar algo ```decimal```.

### ☑️ Boolean (bool)
Boolean, ou ```booleano``` na programação, é um tipo de dado utilizado para representar dois valores possíveis: `True` (verdadeiro) ou `False` (falso).
```python
maior_de_idade = True
menor_de_idade = False
```
Aqui vemos que ```maior_de_idade``` possui o valor ```True```, enquanto ```menor_de_idade``` possui o valor ```False```.
> Para o tipo de dado ```Booleano``` funcionar corretamente, a primeira letra de ```True``` e ```False``` deve ser sempre maiúscula.

## ➕ Operadores
Assim como no Excel, aqui também existem operadores matemáticos. Entretanto, eles são um pouco diferentes daqueles que estamos acostumados a ver no Excel.

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
>  Caso tente adicionar um ```texto``` com um ```inteiro``` ou ```decimal```, o Python retornará um erro. Antes de concatená-los, é necessário converter o ```inteiro``` ou ```decimal``` para ```texto```. Explico como fazer isso em [⚠️ Tratamentos de Erros](#-fundamentos)!

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

### ✖️ Multiplicação ( * )
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
> Ele também faz a mesma coisa com listas, porém eu ainda não expliquei sobre o que é uma lista, caso queira saber, está no tópico  [📦 Listas e Tuplas](#-fundamentos) `NÃO ABORDADO`!

### ✖️ Potenciação ( ** )
Diferente do Excel que utiliza ```^```, aqui utilizamos dois asterísticos ( ```**``` ).
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
O módulo aqui funciona de forma um pouco diferente do Excel. No Excel, ele já é uma função pronta; aqui, você utiliza apenas o operador ```%```:
```python
dividendo = 10
divisor = 3
result = dividendo % divisor
print(result) # Saída: 1
```

### ➗ Quociente ( // )
O quociente aqui funciona de uma forma um pouco diferente do Excel também. No Excel, ele já é uma função pronta; aqui, você utiliza apenas o operador ```//```.
```python
dividendo = 10
divisor = 3
result = dividendo // divisor
print(result) # Saída: 3
```

## 🔀 Estruturas Condicionais
Uma estrutura condicional é, basicamente, uma forma de verificar se uma determinada condição é ```verdadeira``` ou ```falsa```, utilizando estruturas como ```if``` e ```else```.

Ela pode funcionar de diferentes maneiras, dependendo da lógica que você precisa implementar.
### ```if```
```python
idade = 18

if idade >= 10:
    print('Vocẽ é maior de idade.')
```
> ***Importante:*** lembre-se de que o código dentro de um ```if```, ```elif``` ou ```else``` precisa estar indentado (com espaçamento à frente). Caso contrário, o Python retornará um erro.

### ```if``` + ```else```
```python
idade = 18

if idade >= 10:
    print('Você é maior de idade.')
else:
    print('Você é menor de idade.')

# Saída: 'Você é maior de idade.'
```
### ```if``` + ```elif``` + ```else```
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
> o ```elif``` serve para verificar várias possibilidades, em vez de apenas uma.

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
> No Python, existem operadores lógicos como ```and``` (e), ```or``` (ou) e ```not``` (não), semelhantes aos utilizados no Excel.

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