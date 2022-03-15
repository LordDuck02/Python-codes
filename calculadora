```python
import time
import math
#Raiz-Quadrada
def rq():
      numero = float(input("Digite um número: "))
      raiz = math.pow(numero, 1/2)
      print(f"A raiz quadrada de {numero} é {raiz}")
#Raiz-Quadrada
#Potencia
def potencia():
      i = int(input("Digite seu primeiro número:"))
      x = int(input("Digite seu segundo número: "))
      print(i, "**", x, "=", i ** x)

#Potencia
#Porcentagem
def porcentar():
    original = float(input("Qual o valor original?: "))
    desconto = float(input("Qual o valor da porcentagem que você vai descontar?: "))
    valor =  original-(original*desconto)/100
    print(f"O valor final de {original} com o desconto de {desconto} é {valor}") 
#Porcentagem
#Definições
def adicionar(x, y):
      return x + y

def subtrair(x, y):
      return x - y

def dividir(x, y):
      return x / y

def multiplicar(x, y):
      return x * y      
#Definições

print("Bem vindo a calculadora duck!")
time.sleep(0.5)
print("Vamos começar...")
time.sleep(0.5)

ferramenta = input("""Por favor selecione uma função:
                   1-Calculos
                   2-Porcentagem
                   3-Potenciação
                   4-Raiz-Quadrada
                   Resposta: """)

if ferramenta == "4":
      rq()
elif ferramenta == "2":
      porcentar()
elif ferramenta == "3":
      potencia() 
elif ferramenta == "1":
    operador = input("Qual o operador?: ")
    digito1 = int(input("Digite seu primeiro número: "))
    digito2 = int(input("Digite seu segundo número: "))
    if operador == "+":
          print(digito1, "+", digito2, "=", adicionar(digito1, digito2))
    elif operador == "-":
          print(digito1, "-", digito2, "=", subtrair(digito1, digito2))
    elif operador == "*":
          print(digito1, "*", digito2, "=", multiplicar(digito1, digito2))
    elif operador == "/":
          print(digito1, "/", digito2, "=", dividir(digito1, digito2))
```
