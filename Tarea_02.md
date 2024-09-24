# Problema 1: Imprimir los números del 1 al 100

# Utilizamos un bucle for para recorrer del 1 al 100
for num in range(1, 101):
    print(num)
# Problema 2: Imprimir números del 1 al 100 que sean divisibles entre 3

# Bucle for para recorrer del 1 al 100
for num in range(1, 101):
    if num % 3 == 0:  # Verificamos si el número es divisible entre 3
        print(num)
# Problema 3: Sumador y comparador de dos números

# Solicitamos dos números al usuario
numero1 = int(input("Ingresa el primer número: "))
numero2 = int(input("Ingresa el segundo número: "))

# Calculamos la suma de los números
suma = numero1 + numero2

# Comparación según el valor de la suma
if suma < 100:
    print("La suma es menor a 100")
elif 100 <= suma < 150:
    print("La suma es mayor a 100 y menor a 150")
else:
    print("La suma es mayor a 150")
# Problema 4: Calculador de promedio

# Solicitamos la edad y si le gusta la programación
edad = int(input("Ingresa tu edad: "))
gusta_programar = input("¿Te gusta programar? (sí/no): ").lower()

# Verificamos las condiciones
if edad >= 18 and gusta_programar == "sí":
    print("Eres mayor de edad y te gusta programar.")
else:
    print("No eres mayor de edad o no te gusta programar.")

