coeficiente = int(input("coeficiente: "))
variable = input("variable: ")
exponente = int(input("exponente: "))

#TERMINO
print("Su termino es: ",coeficiente,variable,"^",exponente)

#DERIVADA
coeficiente1= coeficiente * exponente
exponente1= exponente - 1
print("Su derivada es: ",coeficiente1,variable,"^",exponente1)

#INTEGRAL
exponente2=exponente+1
print("Su integral es: ", coeficiente,"/",exponente2,variable,"^",exponente2)
