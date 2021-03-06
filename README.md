# hoja-de-trabajo-1.1
#Ejercicio 1 
print('¡Hola a "\'todas"\' y "\'todos!"" )

Ejercicio #2
user_name=input('Ingresa tu nombre: ')
>>> print("¡Hola <" + user_name + ">!")

Ejercicio #3
booleanos = [0, 1]
print('x\ty\tx or y')
print('-'*22)
for x in booleanos:
    for y in booleanos:
        print(x, y, x or y, sep = '\t')
print()

Ejercicio #4
horas=float(input("Ingrese lasshoras de estudio: "))
>>> prom=float(input("Ingrese el promedio por día: "))
>>> suma=(prom+horas)
>>> print("la sumatoria es de: ")
print(suma)

ejercicio #5
m=int(input('ingrese valor: '))
>>> sum=(m*(m+1))/2
>>> print('la suma de las números desde el 1 hasta ')
>>> print(m)
>>> print('es')
>>> print(sum)

ejercicio #6
peso=input('¿Cuál es tu peso en libras? ')
>>> altura=input('¿Cuál es tu estatura en metros? ')
>>> indice=round(float(peso)/float(altura)**2,2)
>>> print('Tu índice de masa corporal es ' +str(indice))

Ejercicio #7
 a=input('Ingrese el dividendo, en enteros: ')
>>> b=input('Ingrese el divisor, en enteros: ')
>>> print(a + ' entre ' + b + ' da un cociente ' + str(int(a) // int(b)) + ' y un residuo de ' + str(int(a)%int(b)))

Ejercicio #8
monto=float(input('¿Monto a invertir? '))
>>> interes=float(input('¿Interés anual? '))
>>> años=int(input('¿A cuántos años? '))
>>> print('El capital será: ' +str(round(monto*(interes/100+1)**años, 2)))

Ejercicio #9
 peso_b=112
 peso_s=75
>>> barreno=int(input('Ingrese el número de barrenos a enviar: '))
>>> sierras=int(input('Ingrese el número de sierras a enviar: '))
>>> peso_e=peso_b*barreno+peso_s*sierras
 print('El peso del paquete será de: ' +str(peso_e)+ 'Kg')

Ejercicio #10
 ram=int(input('Ingrese el número de memorias vendidas que son usadas: '))
>>> costo=20.0
>>> descuento=0.6
>>> venta_f=ram*costo*(1-descuento)
>>> print('El costo de una memoria nueva es de US$'+ str(costo))
>>> print('El descuento de una semi nueva es: ' + str(descuento*100) + '%')
>>> print('La venta final será por US$' + str(round(venta_f,2)))


