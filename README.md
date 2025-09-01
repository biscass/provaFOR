# provaFOR
inicio = int(input("Digite o numero inicial: "))
fim = int(input("Digite o numero final: "))
soma = 0
for numero in range(inicio, fim + 1):
    if numero % 2 == 0:
        soma += numero
else:
    
    if soma == 0:
        print("Nao tem numeros pares neste intervalo. ")


print("Soma dos numeros pares: ", soma)
