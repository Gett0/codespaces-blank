numero = int(input("Introduzca el tamaño de la espiral:\n:>>> "))
resto_filas_arriba, resto_filas_abajo, r, p_lineas = [], [], [], []
# Logica de construcción de la espiral de tamaño N
for d in range(int(numero/2 - 1)):
    param1, param2, param3 = d, numero - (2 * d) - 3, d + 1
    p_lineas = ("║" * param1 + "╔" + "═" * param2 + "╗" + "║" * param3)
    resto_filas_arriba += [p_lineas]
    p_lineas_abajo = ("║" * param1 + '╚' + "═" * (param2 + 1) + '╝' + "║" * (param3 - 1))    
    resto_filas_abajo.append(p_lineas_abajo) 
# Empezamos a imprimir.
print("═" * (numero - 1) + "╗")
for fila_mia in resto_filas_arriba:
    for elemento in fila_mia:
        print(elemento, end="")
    print()
    
if numero % 2 == 0:
    param4 = int((numero/2)-1)
    p_lineas = ("║" * param4 + "╚" +  "╝" + "║" * param4)

for fila_mia3 in reversed(resto_filas_abajo):
    for elemento in fila_mia3:
        print(elemento, end="")
    print()