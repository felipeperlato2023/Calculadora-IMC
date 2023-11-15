# Trabalho Linguagem de programação calculadora imc
import os

 #entradadedados
altura = float(input("Informe sua altura em metros: "))
peso = float(input("Informe seu peso em Kg: "))
 
 #formaula calc imc
imc = peso / altura**2
 
print("Seu IMC é: %.4f" % imc)

#condições
if imc < 16:
	print("Magreza grave")

elif imc < 18.5:
	print("Magreza leve")
elif imc < 25:
	print("Saudável")

    #caso seja cimadopeso
elif imc < 30:
	print("Sobrepeso")

 
os.system("pause")