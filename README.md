# El-meu-primer-repo
Primeres proves de programació amb python
print("Et donem la Benvinguda")
salutacio ="hola"
print ("el teu nom")
nom = input ()
#Variables
n1 = 5
print ("altre numero")
n2 =int (input())
print (n1 + n2)
x = 8
y = str(x)
x=10
y=5
z=10/5
resultat =int (z)
print(resultat)
resposta1 = True
resposta2 = False
print(int(resposta1))
print(float(resposta2))
x = 0.5
y = "pilota"
print (type(x))
print (type (y))
#Diccionari
samarretes={'vermelles' :1, 'blanques' :3, 'blaves' :3, 'negres' : 5  }
claus=samarretes.keys()
print('grogues'in list(claus))
samarretes ['grogues'] = 1
claus = samarretes.keys ()
print('grogues' in list(claus))
print (list (claus). index ('grogues'))
valor_llista= list(samarretes.values())
mitjana=sum(valor_llista)/len(valor_llista)
print('la mitjana de la compra és {:.2f}'.format(mitjana))
print(sum(valor_llista))
#Exgercici diccioanri
compra ={'pomes': 3.56, 'mandarines': 4.35, 'sindria': 6.23, 'maduixes': 4.28, 
         'peres': 2.86, 'taronges': 3.48}
valor_llista= list(compra.values())
print(sum(valor_llista))
print(len(valor_llista))
print ('llimones'in list(compra))
print('entra la nova fruita')
compra ['llimones'] = 8
print ('llimones'in list(compra))
print(sum(valor_llista))
#Estructures condicionals
