# Algoritmo en PSeInt: Números Impares del 1 al 50

## Descripción

Este algoritmo en PSeInt está diseñado para imprimir todos los números impares entre 1 y 50. Utiliza un ciclo `Para` y una condición `SI` para verificar si el número es impar. Los números impares son aquellos que no son divisibles por 2 sin dejar residuo.

## Objetivo

El objetivo de este algoritmo es demostrar cómo utilizar estructuras de control como ciclos (`Para`) y condicionales (`SI`) en PSeInt para iterar a través de un rango de números y seleccionar aquellos que cumplen con una determinada condición (en este caso, ser impares).

## Flujo del Algoritmo

1. El programa inicia un ciclo desde el número 1 hasta el número 50.
2. Dentro del ciclo, verifica si el número actual es impar (es decir, si el residuo de la división entre 2 es distinto de cero).
3. Si el número es impar, lo imprime en pantalla.
4. Continúa con el siguiente número hasta llegar a 50.

## Pseudocódigo en PSeInt

Algoritmo Numeros_1_50_Impares
	Definir num como entero
	num <- 1
	Mientras num <= 50 Hacer
		Escribir num
		num <- num + 2
	FinMientras
FinAlgoritmo
