# projetopy
Instruções do projeto
Precisamos imprimir um número para cada andar de um hotel de 20 andares. Porém, o dono do hotel é supersticioso e optou por não ter um 13ro andar.

Escreva um código que imprima todos os números exceto o número 13.
Escreva mais dois códigos que resolvam o mesmo problema, mas dessa vez usando os outros dois tipos de laços de repetição aprendidos.

Como desafio, imprima eles em ordem decrescente (20, 19, 18...)



i = 0
for i in range (0,20,1 ):
    if i == 13:
        continue
    print(i)
    # continue here

print ("terraço")


andar = 0
while andar <=19:
    andar += 1

    if andar == 13:
        continue

    print(andar)

else:
    print("Terraço")

    for andar in range(21):

        if andar == 13:

            continue
        :
            print(andar)


for andar in range (20,0, -1):
    if andar == 13:
        continue
    else:
        print(andar)
