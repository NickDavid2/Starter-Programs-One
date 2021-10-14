# Starter-Programs-One
My Starter Programs
print(' ' * 10)
print(' ---- EXEMPLO DE LISTAS ----')
print(' ' * 10)
lista1 = ['açucar' , 'feijão' , 'arroz' , 'farinha']
print(lista1)
print(' ' * 10)
# REMOVER NOME
lista1.remove('açucar')
print(lista1)
print(' ' * 10)
#REMOVER - DA POSIÇÃO
lista1.pop(2)
print(lista1)
print(' ' * 10)
# ADICIONAR ELEMENTO (1ª FORMA)
lista1.append('mortadela')
print(lista1)
print(' ' * 10)
# ADICIONAR ELEMENTO (2ª FORMA)
lista1[0] = 'macarrão'
print(lista1)
print(' ' * 10)
lista1.insert(2, 'abacaxi') # ADICIONAR ELEMENTO (3ª FORMA)
print(lista1)
print(' ' * 10)
print(' ---- EXEMPLO DE TUPLAS ----')
print(' ' * 10)
tuplas1 = ('açucar' , 'feijão' , 'arroz' , 'farinha')
print(tuplas1)
print(' ' * 10)
#IMPRIMIR TIPOS DE TUPLAS
print(type(tuplas1))
print(' ' * 10)
#IMPRIMIR QTD DE TUPLAS
print(len(tuplas1))
print(' ' * 10)

print(' ---- EXEMPLO DE DICIONÁRIOS ----')
print(' ' * 10)
dicion2 = {'NOME': 'Zezinho',
           'TELEFONE': '9999-9999',
           'ALTURA': 1.60
           }
print(dicion2)
print(' ' * 10)

#REMOVER
dicion2.pop('NOME')
print(dicion2)

#ADICIONAR
dicion2['TIME'] = 'Bahia'
dicion2['NOME'] = 'Joseph'
print(dicion2)





