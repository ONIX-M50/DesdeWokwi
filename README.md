![](../../workflows/gds/badge.svg) ![](../../workflows/docs/badge.svg) ![](../../workflows/wokwi_test/badge.svg)

# Sumador/Sustractor de 3 bits con acarreo y prestamo.

Este es un pequeño proyecto para la inciativa VLSI de la rama estudiantil IEEE, del que, se ha partido de una plantilla predefinida de 8 entradas y 8 salidas para diseñar nuestro propio circuito. 
Dicho circuito consta de un arreglo lógico que recibe 2 numeros de 3 bits y opcionalmente un bit de acarreo y uno de prestamo, con los que realiza tanto su suma como su resta y las entrega a la salida (en 4 bits cada resultado).

## Principales usos

Se puede implementar para la adición y sustracción constante de 2 numeros binarios de 1 a 3 bits. Sin embargo, en caso de requerirse la operación entre 2 numeros con más de 3 bits, se pueden implementar más de un integrado, ya que el circuito acepta y proporciona bits de acarreo y prestamo. Un ejemplo de ello es: asumir que se requiere sumar 2 números de 8 bits cada uno, por lo que se pueden implementar 3 integrados en secuencia simplemente conectando el bit de acarreo de salida del primer integrado al bit de acarreo de entrada del segundo integrado y asi sucesivamente.

## Resources

- [FAQ](https://tinytapeout.com/faq/)
- [Digital design lessons](https://tinytapeout.com/digital_design/)
- [Learn how semiconductors work](https://tinytapeout.com/siliwiz/)
- [Join the community](https://discord.gg/rPK2nSjxy8)
