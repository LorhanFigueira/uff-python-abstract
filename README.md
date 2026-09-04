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
- [➕ Operadores](#-operadores)
- [🔀 Estruturas Condicionais](#-fundamentos)
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

## ☑️ Boolean (bool)
Boolean, ou ```booleano``` na programação, é um tipo de dado utilizado para representar dois valores possíveis: `True` (verdadeiro) ou `False` (falso).
```python
maior_de_idade = True
menor_de_idade = False
```
Aqui vemos que ```maior_de_idade``` possui o valor ```True```, enquanto ```menor_de_idade``` possui o valor ```False```.
> Para o tipo de dado ```Booleano``` funcionar corretamente, a primeira letra de ```True``` e ```False``` deve ser sempre maiúscula.