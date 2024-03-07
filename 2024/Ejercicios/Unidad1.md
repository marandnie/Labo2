# Universidad Nacional de San Martín
## Guía de Ejercicios
### Unidad 1: Variables, ciclos y control de flujo
1. Ejercicios

    1. Comparación de dos números

    Escribe un programa que solicite al usuario ingresar dos números enteros y luego imprima el mayor de los dos. Si son iguales que imprima ’son iguales’.

    2. Verificación de número par o impar

    Desarrolla un programa que solicite al usuario ingresar un número entero e imprima si es par o impar.
   
    Ayuda: La siguiente sentencia verifica si el resto de dividir num por 2 es 0.

    num % 2 == 0
   
    3. Verificación de año bisiesto

    Escribe un programa que solicite al usuario ingresar un año e imprima si es bisiesto o no. Un año es bisiesto si es divisible por 4 pero no por 100, o si es divisible por 400.
   
    4. Categorización de edad

    Desarrolla un programa que solicite al usuario ingresar su edad e imprima en qué categoría se encuentra (niño, adolescente, adulto).

    5. Determinación del tipo de triángulo
    
    Escribe un programa que solicite al usuario ingresar las longitudes de los tres lados de un triángulo y determine si es equilátero, isósceles o escaleno.
   
    6. Conteo Regresivo para el Despegue
    
    Implementa un programa que simule un conteo regresivo para el despegue de un cohete. El usuario debe ingresar un número entero positivo y el programa debe imprimir los números desde ese número hasta 0.
   
    7. Cuenta de Ahorro
    
    Crea un programa que simule una cuenta de ahorro. El usuario ingresa la cantidad de dinero que quiere ahorrar mensualmente. El programa debe calcular cuánto dinero habrá acumulado en un año considerando un interés fijo mensual
del 35%.

    8. Calculadora de Gastos
    
    Desarrolla una calculadora de gastos que solicite al usuario ingresar el precio de varios productos y luego calcule el total. El programa debe continuar pidiendo precios hasta que el usuario decida detenerse.
   
    9. Generador de Tablas de Multiplicar

    Crea un programa que solicite al usuario ingresar un n´umero y luego imprima la tabla de multiplicar de ese número del 1 al 10.

    10. Calculadora de Índice de Masa Corporal (IMC)

    Escribe un programa que calcule el IMC de una persona. El usuario debe ingresar su peso en kilogramos y su altura en metros. El programa debe imprimir el IMC y una categoría correspondiente (bajo peso, peso normal, sobrepeso, etc.).

    11. Conversor de Temperatura
    
    Crea un programa que convierta la temperatura de grados Celsius a Fahrenheit. El usuario debe ingresar la temperatura en Celsius y el programa debe imprimir la temperatura equivalente en Fahrenheit.

    12. Juego de Adivinar el Número
    
    Desarrolla un juego en el que el programa selecciona un número aleatorio entre 1 y 100, y el usuario intenta adivinarlo. El programa debe dar pistas (mayor/-menor) y contar el número de intentos.
   
    Ayuda: Use el siguiente codigo para generar un numero aleatorio.

    ```
    #include <stdio.h>
    #include <stdlib.h>
    #include <time.h>
    int main() {
    srand(time(NULL));
    int numero_secreto = rand() % 100 + 1; // Genera un n´umero aleatorio entre 1 y 100
    //inserte su codigo aqui
    return 0;
    }
    ```
    13. Ordenamiento de Números
    
    Escribe un programa que solicite al usuario ingresar tres números y luego los imprima en orden ascendente.

    14. Validación de Edad para Acceso

    Desarrolla un programa que solicite al usuario ingresar su edad. Si es mayor de 18 años, imprime ”Bienvenido/a”; de lo contrario, imprime ”Acceso denegado”.

    15. Calculadora de Factorial

    Crea un programa que solicite al usuario ingresar un número entero no negativo y luego calcule su factorial.

    16. Simulación de Cajero Automático (switch case)

    Desarrolla un programa que simule un cajero automático. El usuario puede realizar depósitos, retiros y consultar su saldo.
