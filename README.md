# Lab02-DataScienceAcademy-CalculadoraSimples
#Calculadora simples desafio DSA. - Python

operacao = int(input("Selecione o número da operação desejada: "))
 print("1 - Soma/n 2 - Subtração/n 3 - Multiplicação/n 4 - Divisão")
 n1 = int(input("Digite o primeiro número"))
 n2 = int(input("Digite o segundo número"))
 
 if operacao == 1:
   soma = n1 + n2
   print("soma")
 elif operacao == 2:
   subtracao = n1 - n2
   print("subtracao")
 elif operacao == 3:
   multiplicacao = n1 * n2
   print("multiplicacao")
 elif operacao == 4:
   if n2 == 0:
     print("O número não pode ser dividido por zero.")
   else:
     divisao = n1 // n2
     print("divisao")
 else
   print("Essa operação não existe.")
