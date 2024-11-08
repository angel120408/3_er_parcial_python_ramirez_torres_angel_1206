# Codigo #1
- Codigop creado por Ramirez Torres Angel Manuel de 3°W

print("CODIGO #1")
print(" ")#espacio entre lineas 
print("Ramirez Torres Angel Manuel De 3°W")#Nos muestra el nombre, grado y grupo del alumno
print(" ")#espacio entre lineas 
print("Numero de control: 1206")#Nos muestra el numero de control del alumndo 
print(" ")#espacio entre lineas 
print("-INSRTUCCIONES-")#Imprime las instrucciones 
print(" ")#espacio entre lineas 
print("Comprueba si una edad almacenada en una variable es mayor de edad, es decir, que su valor que sea")
print("mayor de 18. Si es así, imprime el texto Eres mayor de edad. En caso contrario, imprime el texto")
print("NO eres mayor de edad.")
#Fin de las instrucciones 
print(" ")#espacio entre lineas 

#Solicita al usuario ingresar su edad 
edad = int(input("Introduce tu edad: "))

print(" ")#espacio entre lineas

#Pone una condicion para saber si es o no mayor de edad 
if edad > 18:
    print("Eres mayor de edad")  #Imprime este mensaje si es mayor 
else:
    print("NO eres mayor de edad")  #Imprime este mensaje si es menor 
![image](https://github.com/user-attachments/assets/173af4c9-26df-4b89-92cb-e889f674ca52)
![image](https://github.com/user-attachments/assets/3067e364-5860-4332-95e7-af06a867aada)


# Codigo #2
- Codigop creado por Ramirez Torres Angel Manuel de 3°W

print("CODIGO #2")
print(" ")#espacio entre lineas 
print("Ramirez Torres Angel Manuel De 3°W")#Nos muestra el nombre, grado y grupo del alumno
print(" ")#espacio entre lineas 
print("Numero de control: 1206")#Nos muestra el numero de control del alumndo 
print(" ")#espacio entre lineas 
print("-INSRTUCCIONES-")#Imprime las instrucciones 
print(" ")#espacio entre lineas 
print("Dada una nota almacenada en una variable, imprime su equivalente:")
print("• Mayor o igual a 0, pero menor que 5, SUSPENSO.")
print("• Mayor o igual a 5, pero menor que 6, SUFICIENTE.")
print("• Mayor o igual a 6, pero menor que 7, BIEN.")
print("• Mayor o igual a 7, pero menor que 9, NOTABLE.")
print("• Mayor o igual a 9, pero menor o igual a 10, SOBRESALIENTE.")
print("En cualquier otro caso, imprimir el texto: NOTA NO VÁLIDA.")
#Fin de las instrucciones 
print(" ")#espacio entre lineas 

def evaluar_nota(nota):
    # Verifica el rango de la nota y retorna el mensaje correspondiente
    if 0 <= nota < 5:
        return "SUSPENSO"
    elif 5 <= nota < 6:
        return "SUFICIENTE"
    elif 6 <= nota < 7:
        return "BIEN"
    elif 7 <= nota < 9:
        return "NOTABLE"
    elif 9 <= nota <= 10:
        return "SOBRESALIENTE"
    else:
        return "NOTA NO VÁLIDA"  # Para valores fuera del rango 0-10

# Solicita al usuario que ingrese la nota y la convierte a un número flotante
nota = float(input("Introduce la nota: "))

# Llama a la función y muestra el resultado
print(evaluar_nota(nota))

![image](https://github.com/user-attachments/assets/11f0dddd-c94b-42e5-995c-f37f8c7ff2d0)
![image](https://github.com/user-attachments/assets/51e75658-7bf1-4042-9c5c-9732a33925ca)




# Codigo #3
- Codigop creado por Ramirez Torres Angel Manuel de 3°W

print("CODIGO #3")
print(" ")#espacio entre lineas 
print("Ramirez Torres Angel Manuel De 3°W")#Nos muestra el nombre, grado y grupo del alumno
print(" ")#espacio entre lineas 
print("Numero de control: 1206")#Nos muestra el numero de control del alumndo 
print(" ")#espacio entre lineas 
print("-INSRTUCCIONES-")#Imprime las instrucciones
print(" ")#espacio entre lineas 
print("Existen dos variables, una con un nombre y otra con un apellido. Primero se ha de comprobar el")
print("nombre, si es igual a Daniel, se comprueba el apellido, si es igual a Ramos, se imprime por")
print("pantalla el texto Nombre y apellido correctos. En caso de que el nombre sea Daniel,")
print("pero el apellido no sea Ramos, se imprime por pantalla el texto Apellido incorrecto. En")
print("caso que el nombre no sea Daniel, se imprime por pantalla el texto Usuario desconocido.")
#Fin de las instrucciones 
print(" ")#espacio entre lineas

# Solicita al usuario que ingrese el nombre y el apellido
nombre = input("Introduce tu nombre: ")
apellido = input("Introduce tu apellido: ")

# Comprobación del nombre y el apellido
if nombre == "Daniel":
    if apellido == "Ramos":
        print("Nombre y apellido correctos")  # Ambos nombre y apellido coinciden
    else:
        print("Apellido incorrecto")  # Nombre coincide, pero apellido no
else:
    print("Usuario desconocido")  # Nombre no coincide

![image](https://github.com/user-attachments/assets/c3500bfe-cff7-4409-8967-0d7c01671918)
![image](https://github.com/user-attachments/assets/f949e511-3685-495c-b7c4-9944e472d1b3)



# Codigo #1
- Codigop creado por Ramirez Torres Angel Manuel de 3°W





# Codigo #1
- Codigop creado por Ramirez Torres Angel Manuel de 3°W


# Codigo #1
- Codigop creado por Ramirez Torres Angel Manuel de 3°W





# Codigo #1
- Codigop creado por Ramirez Torres Angel Manuel de 3°W





# Codigo #1
- Codigop creado por Ramirez Torres Angel Manuel de 3°W





# Codigo #1
- Codigop creado por Ramirez Torres Angel Manuel de 3°W
