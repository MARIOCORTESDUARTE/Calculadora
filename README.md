# Calculadora
CCalculadora em Python Mario Duarte Fevereiro 2025
#
# Calculadora em Python
# Mario Duarte
# Fevereiro/2025
print("\n******************* Calculadora em Python *******************")
print("\n*************************************************************")
print("\n ")

# Definição das funções básicas: Soma, Subtração, Multiplicação e Divisão

# Soma
add = lambda x, y: [x + y]

# Subtração
subtract = lambda x, y: [x - y]

# Multiplicação
multiply = lambda x, y: [x * y]

# Divisão
divide = lambda x, y: [x / y]

# Escolha da operação e números

print("\nSelecione o número da operação desejada: \n")
print("1 - Soma")
print("2 - Subtração")
print("3 - Multiplicação")
print("4 - Divisão")

escolha = input("\nDigite sua opção (1/2/3/4): ")

num1 = int(input("\nDigite o primeiro número: "))
num2 = int(input("\nDigite o segundo número: "))

# Verifica opção escolhida e executa a operação
if escolha == '1':
    resultado = add(num1, num2)
    print("\n")
    print(resultado)
    print("\n")

elif escolha == '2':
    resultado = subtract(num1, num2)
    print("\n")
    print(resultado)
    print("\n")

elif escolha == '3':
    resultado = multiply(num1, num2)
    print("\n")
    print(resultado)
    print("\n")

elif escolha == '4':
    resultado = divide(num1, num2)
    print("\n")
    print(resultado)
    print("\n")

else:
    print("\nOpção Inválida!")
#
Exemplo:
******************* Calculadora em Python *******************

*************************************************************

 

Selecione o número da operação desejada: 

1 - Soma
2 - Subtração
3 - Multiplicação
4 - Divisão

Digite sua opção (1/2/3/4): 3

Digite o primeiro número: 20

Digite o segundo número: 30


[600]
