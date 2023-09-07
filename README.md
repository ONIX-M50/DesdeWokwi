![](../../workflows/gds/badge.svg) ![](../../workflows/docs/badge.svg) ![](../../workflows/wokwi_test/badge.svg)

# Sumador/Sustractor de 3 bits con acarreo y prestamo.

Este es un pequeño proyecto para la inciativa VLSI de la rama estudiantil IEEE. 
Para su diseño se ha partido de una plantilla predefinida de 8 entradas y 8 salidas para diseñar nuestro propio circuito. Dicho circuito consta de un arreglo lógico que recibe 2 numeros de 3 bits y opcionalmente un bit de acarreo y uno de préstamo, con los que realiza tanto su suma como su resta y las entrega a la salida (en 4 bits cada resultado).

## Uso principal

Se puede implementar para la adición y sustracción constante de 2 números binarios de 1 a 3 bits. Sin embargo, en caso de requerirse la operación entre 2 numeros con más de 3 bits, se pueden implementar más de un integrado, ya que el circuito acepta y proporciona bits de acarreo y préstamo. Un ejemplo de ello es: asumir que se requiere sumar 2 números de 8 bits cada uno, por lo que se pueden implementar 3 integrados en secuencia simplemente conectando el bit de acarreo de salida del primer integrado al bit de acarreo de entrada del segundo integrado y asi sucesivamente.

## Descripción de los pines
Entradas:
- IN1 primer bit del primer número
- IN2 segundo bit del primer número
- IN3 tercer bit del primer número
- IN4 bit de acarreo para la suma de ambos números
- IN5 primer bit del segundo número
- IN6 segundo bit del segundo número
- IN7 tercer bit del segundo número
- IN8 bit de préstamo para la resta de ambos números

Salidas:
- OUT1 primer bit del resultado de la suma
- OUT2 segundo bit del resultado de la suma
- OUT3 tercer bit del resultado de la suma
- OUT4 bit de acarreo del resultado de la suma
- OUT5 primer bit del resultado de la resta
- OUT6 segundo bit del resultado de la resta
- OUT7 tercer bit del resultado de la resta
- OUT8 bit de préstamo del resultado de la resta
