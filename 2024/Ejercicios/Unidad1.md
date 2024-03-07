Universidad Nacional de San Martín
Guía de Ejercicios
Unidad 1: Variables, ciclos y control de flujo
1 Ejercicios
1.1 Comparaci´on de dos n´umeros
Escribe un programa que solicite al usuario ingresar dos n´umeros enteros y luego
imprima el mayor de los dos. Si son iguales que imprima ’son iguales’.
1.2 Verificaci´on de n´umero par o impar
Desarrolla un programa que solicite al usuario ingresar un n´umero entero e
imprima si es par o impar.
Ayuda: La siguiente sentencia verifica si el resto de dividir num por
2 es 0
num % 2 == 0
1.3 Verificaci´on de a˜no bisiesto
Escribe un programa que solicite al usuario ingresar un a˜no e imprima si es
bisiesto o no. Un a˜no es bisiesto si es divisible por 4 pero no por 100, o si es
divisible por 400.
1.4 Categorizaci´on de edad
Desarrolla un programa que solicite al usuario ingresar su edad e imprima en
qu´e categor´ıa se encuentra (ni˜no, adolescente, adulto).
1.5 Determinaci´on del tipo de tri´angulo
Escribe un programa que solicite al usuario ingresar las longitudes de los tres
lados de un tri´angulo y determine si es equil´atero, is´osceles o escaleno.
1.6 Conteo Regresivo para el Despegue
Implementa un programa que simule un conteo regresivo para el despegue de
un cohete. El usuario debe ingresar un n´umero entero positivo y el programa
debe imprimir los n´umeros desde ese n´umero hasta 0.
1.7 Cuenta de Ahorro
Crea un programa que simule una cuenta de ahorro. El usuario ingresa la
cantidad de dinero que quiere ahorrar mensualmente. El programa debe calcular
cu´anto dinero habr´a acumulado en un a˜no considerando un inter´es fijo mensual
del 35%.
1
1.8 Calculadora de Gastos
Desarrolla una calculadora de gastos que solicite al usuario ingresar el precio de
varios productos y luego calcule el total. El programa debe continuar pidiendo
precios hasta que el usuario decida detenerse.
1.9 Generador de Tablas de Multiplicar
Crea un programa que solicite al usuario ingresar un n´umero y luego imprima
la tabla de multiplicar de ese n´umero del 1 al 10.
1.10 Calculadora de ´Indice de Masa Corporal (IMC)
Escribe un programa que calcule el IMC de una persona. El usuario debe
ingresar su peso en kilogramos y su altura en metros. El programa debe imprimir
el IMC y una categor´ıa correspondiente (bajo peso, peso normal, sobrepeso,
etc.).
1.11 Conversor de Temperatura
Crea un programa que convierta la temperatura de grados Celsius a Fahrenheit.
El usuario debe ingresar la temperatura en Celsius y el programa debe imprimir
la temperatura equivalente en Fahrenheit.
1.12 Juego de Adivinar el N´umero
Desarrolla un juego en el que el programa selecciona un n´umero aleatorio entre
1 y 100, y el usuario intenta adivinarlo. El programa debe dar pistas (mayor/-
menor) y contar el n´umero de intentos.
Ayuda: Use el siguiente codigo para generar un numero aleatorio
#include <stdio.h>
#include <stdlib.h>
#include <time.h>
int main() {
srand(time(NULL));
int numero_secreto = rand() % 100 + 1; // Genera un n´umero aleatorio entre 1 y 100
//inserte su codigo aqui
return 0;
}
1.13 Ordenamiento de N´umeros
Escribe un programa que solicite al usuario ingresar tres n´umeros y luego los
imprima en orden ascendente.
2
1.14 Validaci´on de Edad para Acceso
Desarrolla un programa que solicite al usuario ingresar su edad. Si es mayor de
18 a˜nos, imprime ”Bienvenido/a”; de lo contrario, imprime ”Acceso denegado”.
1.15 Calculadora de Factorial
Crea un programa que solicite al usuario ingresar un n´umero entero no negativo
y luego calcule su factorial.
1.16 Simulaci´on de Cajero Autom´atico(switch case)
Desarrolla un programa que simule un cajero autom´atico. El usuario puede
realizar dep´ositos, retiros y consultar su saldo.
3
