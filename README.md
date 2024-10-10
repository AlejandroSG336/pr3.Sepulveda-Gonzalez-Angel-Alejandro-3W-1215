# pr3.Sepulveda-Gonzalez-Angel-Alejandro-3W-1215

# 3. Función que toma un entero positivo y devuelve su factorial

def factorial(n):

  # Verificamos que el número sea positivo
    
  if n < 0:
    
  # Si el número es negativo, devolvemos un mensaje de error
        
  return "El número debe ser positivo"
    
  # Caso base del factorial: 0! = 1
    
  elif n == 0:
    
  # Devolvemos 1 para el caso de 0!
        
   return 1
        
  else:
  
  # Calculamos el factorial iterativamente
        
  resultado = 1
        
   # Iteramos desde 1 hasta el número n
        
  for i in range(1, n + 1):
        
   # Multiplicamos el resultado por cada número de la iteración
            
   resultado *= i
        
  # Devolvemos el resultado final
        
  return resultado

# Ejemplo de uso:

numero = 5

print(f"El factorial de {numero} es: {factorial(numero)}")

![image](https://github.com/user-attachments/assets/a19254c7-a053-4052-95cc-8f5c29521b35)
![image](https://github.com/user-attachments/assets/e29b22f7-edab-48d0-a84c-aa27eb7d1aab)

