#las variable se pueden semar. como? de esta manera
hola_mundo = 'hola' + ' mundo'
print(hola_mundo)
print(len(hola_mundo))       # OJO ACA: ''len'' cuenta las palabras

nombre = 'franco dominguez'
print(nombre.title())           # title(): las primeras palabras a mayuscula. upper():todo mayuscula. lower(): todo minuscula
print(nombre.upper())
print(nombre.lower())

#operadores
print('buenos aires' == 'pilar')
print('buneos aires' != 'buenos aires')

#rstrip() ..... en opinion es mejor strip() porque combina rstrip() y lstrip()
nombre = "franco dominguez---      "
print(nombre.title().strip('- '))

#valor de una variable dentro de una cadena
nombre = 'luis'
apellido = 'gutierrez'
nombre_completo = f"hola {nombre} {apellido} como estas!!"
print(nombre_completo.title())
