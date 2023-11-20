# Lab02-DataScienceAcademy-CalculadoraSimples
#Calculadora simples desafio DSA. - Python
print("Bem vindo a calculadora de teste do desafio DSA 02/nSelecione a operação que deseja realizar:/n1 - Soma/n2 - Subtração/n3 - Multiplicação/n4 - Divisão")
operacao = int(input("Selecione o número da operação desejada: "))
n1 = int(input("Digite o primeiro número"))
n2 = int(input("Digite o segundo número"))
 
if operacao == 1:
   soma = n1 + n2
   print("O resultado da operação é: ", soma)
elif operacao == 2:
   subtracao = n1 - n2
   print("O resultado da operação é: ", subtracao)
elif operacao == 3:
   multiplicacao = n1 * n2
   print("O resultado da operação é: ", multiplicacao)
elif operacao == 4:
  if n2 == 0:
    print("O número não pode ser dividido por zero.")
  else:
    divisao = n1 // n2
    print("O resultado da operação é: ", divisao)
else:
   print("Essa operação não existe.")
