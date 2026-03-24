# Lista de Exercícios – Python 02

## Informações gerais
**Disciplina**: Introdução à Lógica e Programação  
**Tópicos**:
- `print`, 
- `input`, 
- variáveis e operações aritméticas

---
> **Dica 01:** Use `f-string` para as saídas com valores de variáveis.

> **Dica 02:** Em todos os exercícios que utilizam `input`, lembre-se de converter o valor lido para o tipo adequado usando `int()` ou `float()` quando necessário.

---
## Parte 1 – Comando `print`

**1.** Escreva um programa que exiba na tela a mensagem:
```
Olá, Mundo!
```

**2.** Escreva um programa que exiba seu nome completo na tela.

**3.** Escreva um programa que exiba, em linhas separadas:
```
Nome: Ana
Idade: 15
Curso: Infoweb
```

**4.** Escreva um programa que exiba a seguinte sequência de números, cada um em uma linha:
```
1
2
3
4
5
```

**5.** Escreva um programa que exiba o seguinte texto formatado:
```
*****
*   *
*****
```

**6.** Escreva um programa que exiba, utilizando um único comando `print`, as palavras "Python", "é" e "incrível" separadas por espaço.

**7.** Escreva um programa que exiba a frase "Programar é divertido!" sem o caractere de nova linha ao final (use o parâmetro `end`).

**8.** Escreva um programa que exiba dois valores separados por vírgula usando o parâmetro `sep` do `print`:
```
10,20
```

**9.** Escreva um programa que exiba a tabuada do 2 de 1 a 5 (apenas os resultados, um por linha):
```
2
4
6
8
10
```

**10.** Escreva um programa que exiba a seguinte tabela simples:
```
Produto    Preço
Caneta     2.50
Caderno    12.00
Borracha   1.75
```

---
## Parte 2 – Variáveis

**11.** Declare uma variável chamada `nome` com o valor `"Maria"` e exiba o conteúdo dessa variável.

**12.** Declare duas variáveis, `cidade` e `estado`, e exiba uma mensagem no formato:
```
Eu moro em Natal, RN.
```

**13.** Declare uma variável `ano_nascimento` com o valor `2010` e exiba uma mensagem informando o ano de nascimento.

**14.** Troque os valores de duas variáveis `a = 5` e `b = 10` e exiba os novos valores após a troca.

**15.** Declare três variáveis `x`, `y` e `z` com os valores `1`, `2` e `3` respectivamente. Exiba a soma das três variáveis.

**16.** Crie uma variável `mensagem` que armazene a string `"Aprendendo Python"`. Exiba o conteúdo da variável.

**17.** Declare uma variável `preco` com o valor `49.90` e exiba a mensagem:
```
O preço do produto é R$ 49.90
```

**18.** Declare uma variável `ativo` com o valor booleano `True` e exiba o seu valor.

**19.** Atribua o valor `100` a uma variável `pontos`. Em seguida, some `50` a essa variável e exiba o resultado.

**20.** Crie variáveis para armazenar nome, idade e nota de um aluno. Exiba as informações em formato de relatório:
```
Aluno: João
Idade: 16
Nota: 8.5
```

---
## Parte 3 – Comando `input`

**21.** Escreva um programa que solicite o nome do usuário e exiba a mensagem `"Olá, <nome>!"`. 

**22.** Escreva um programa que peça a cidade do usuário e exiba:
```
Você mora em <cidade>.
```

**23.** Escreva um programa que solicite dois números inteiros e exiba cada um deles em uma linha separada.

**24.** Escreva um programa que peça o nome e a idade do usuário e exiba:
```
<nome> tem <idade> anos.
```

**25.** Escreva um programa que solicite o ano de nascimento do usuário (como inteiro) e exiba-o na tela.

**26.** Escreva um programa que peça ao usuário uma palavra e exiba a mensagem:
```
Você digitou: <palavra>
```

**27.** Escreva um programa que solicite o nome de um produto e o seu preço (como número real) e exiba:
```
Produto: <nome>
Preço: R$ <preço>
```

**28.** Escreva um programa que peça três notas de um aluno (como números reais) e exiba cada nota lida em uma linha separada.

**29.** Escreva um programa que solicite o nome de duas pessoas e exiba:
```
Pessoa 1: <nome1>
Pessoa 2: <nome2>
```

**30.** Escreva um programa que leia um número inteiro e exiba sua versão com `float` (número real).

---
## Parte 4 – Operações Aritméticas

**31.** Leia dois números inteiros e exiba a sua **soma**.

**32.** Leia dois números inteiros e exiba a sua **subtração**.

**33.** Leia dois números reais e exiba o seu **produto** (multiplicação).

**34.** Leia dois números reais e exiba o resultado da **divisão** do primeiro pelo segundo.

**35.** Leia dois números inteiros e exiba o resultado da **divisão inteira** (sem parte decimal) do primeiro pelo segundo.

**36.** Leia dois números inteiros e exiba o **resto da divisão** do primeiro pelo segundo.

**37.** Leia um número e exiba o seu **quadrado** (potência 2).

**38.** Leia um número e exiba o seu **cubo** (potência 3).

**39.** Leia três notas de um aluno e exiba a **média aritmética** com duas casas decimais.

**40.** Leia o valor do salário de um funcionário e exiba o valor do **bônus de 15%** sobre o salário.

---
## Parte 5 – Problemas Combinados

**41.** Leia o nome de um aluno e suas três notas bimestrais. Calcule e exiba a média final com a seguinte saída:
```
Aluno: <nome>
Média: <média>
```

**42.** Leia o preço unitário de um produto e a quantidade comprada. Exiba o **valor total** da compra.

**43.** Leia a base e a altura de um retângulo. Calcule e exiba a **área** do retângulo.

**44.** Leia o raio de um círculo. Considere π = 3.14159. Calcule e exiba a **área** do círculo com duas casas decimais.

**45.** Leia a temperatura em **Celsius** e converta para **Fahrenheit** usando a fórmula `F = C * 9/5 + 32`. Exiba o resultado.

**46.** Leia a distância percorrida (em km) e o tempo gasto (em horas). Calcule e exiba a **velocidade média** (km/h).

**47.** Leia o valor de um produto e o percentual de desconto. Calcule e exiba o **valor final** após o desconto.

**48.** Leia dois números inteiros e exiba:
- A soma
- A subtração
- O produto
- A divisão (com duas casas decimais)

**49.** Leia a quantidade de horas trabalhadas e o valor pago por hora. Calcule e exiba o **salário total** do trabalhador.

**50.** Leia o ano de nascimento de uma pessoa e o ano atual. Calcule e exiba a **idade aproximada** da pessoa.

---
