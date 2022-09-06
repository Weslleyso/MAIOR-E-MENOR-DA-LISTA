# MAIOR-E-MENOR-DA-LISTA

listanum = []
mai = 0
men = 0

for c in range (0,5):
    listanum.append(int(input('Insira um número: ')))

    if c  == 0:
        mai = men = listanum[c]
    else:
        if listanum[c] > mai:
            mai = listanum[c]
        if listanum[c] < men:
            men = listanum[c]

for c, v in enumerate(listanum):
    print(f'na posição {c} encontrei o valor {v}')


print(f'o maior valor digitado foi {mai}')
print(f'o menor valor digitado foi {men}')
print('fim de lista')   
