

A simple calculator made in Python that performs:

- Addition
- Subtraction
- Multiplication
- Division

This project was created to practice basic programming concepts such as:
- Variables
- User input
- Conditional statements

Author: Jywlly Ann Foyes Gittens


numero1 = float(input("Digite o primeiro número: "))
numero2 = float(input("Digite o segundo número: "))

print("Escolha a operação:")
print("1 - Soma")
print("2 - Subtração")
print("3 - Multiplicação")
print("4 - Divisão")

operacao = input("Digite o número da operação desejada: ")

if operacao == "1":
    resultado = numero1 + numero2
    print(f"Resultado da soma: {resultado}")
elif operacao == "2":
    resultado = numero1 - numero2
    print(f"Resultado da subtração: {resultado}")
elif operacao == "3":
    resultado = numero1 * numero2
    print(f"Resultado da multiplicação: {resultado}")
elif operacao == "4":
    resultado = numero1 / numero2
    print(f"Resultado da divisão: {resultado}")
