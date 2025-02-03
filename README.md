print("==================================\n")
print("===========CALCULADORA============\n")
print("==================================")

num1 = float(input("Digite um número:\n"))
num2 = float(input("Digite outro número número:\n"))

operacao = input("Certo! Agora preciso saber qual operação matemática deseja realizar: \n")

result = 0


if  operacao == "+":
    result = num1 + num2

elif operacao == "-":
    result = num1 - num2

elif operacao == "*":
    result = num1 * num2

elif operacao == "/":
    if num2 != 0:
        result =  num1 / num2



print("O resultado da operação é :" , result)

print("==================================")
print("**********************************")
print("==================================")
