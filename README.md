# codigos_Cristian
meus codigos da aula
nome = input("qual é seu nome? ")

peso = float (input("quantos KG  você pesa? "))

altura = float (input("quantos de altura vc tem? "))
print("=== CALCULADORA DE IMC ===")


imc = peso / (altura ** 2)
imc_arredontado = round(imc,2)
if imc < 18.5:
    print(f"olá {nome} você está baixo do {imc_arredontado} peso,tente se alimentar mais,ou faz academia🥗")
    
#se o imc é menor igual a 18.5
elif imc > 18.5 and imc <= 24.9:
    print(f"olá {nome} seu imc é {imc_arredontado} peso normal,está saudavel continue assim👌")

#se o imc é menor igual a 25.0 e maior igual a 29.9
elif imc > 25.0 and imc <= 29.9:
    print(f"olá {nome} seu imc é {imc_arredontado} sobrepeso,é recomendado fazer academia🏋️")

#se o imc é menor igual a 30.0 e maior igual a 34.9
elif imc > 30.0 and imc <= 34.9:
    print(f"olá {nome} seu imc é {imc_arredontado} obesidade grau 1,Procure um nutricionista para obesidade grau 1👍")

#se o imc é menor igual a 35.0 e maior igual a 39.9
elif imc > 35.0 and imc <= 39.9:
    print(f"olá {nome} seu imc é {imc_arredontado} obesidade grau 2,Procure um nutricionista para obesidade grau 2🤙")

#se o imc é menor igual a 40.0
elif imc >= 40.0:
    print(f"olá {nome} seu imc é {imc_arredontado} obesidade grau 3,Procure um nutricionista para obesidade grau 3🤝")

else:
    print("entrada ivalida. digite apenas numeros positivos")
