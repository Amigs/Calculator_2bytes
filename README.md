# Calculator_2bytes

### Requirements:
1. El sistema se debe comportar como una calculadora ( +, -, x, /) con resultados de números de hasta 16bits positivos y negativos.
2. El sistema tendrá 6 pulsadores para la entrada de datos así:
 * Cuatro (4) pulsadores que corresponden al ingreso de unidades, decenas, centenas y miles, al pulsar un número de veces cada uno de estos debe incrementar el valor (según sea, decena, etc..) e ir mostrando el número que se va ingresando en los LEDS de forma binaria.
 * Un pulsador para cambiar entre las 4 posibilidades de operaciones por cada pulsación, suma, resta multiplicación y división. Se debe mostrar en los 4 bits menos significativos de los LEDS. LED[0]->suma, LED[1]->resta, LED[2]->multiplicación, LED[3]->división.
 * Un pulsador para confirmar la operación (ENTER) con una pulsación, y dos pulsaciones para cancelar la operación (BORRAR o RESET).
3. El sistema debe soportar resultados de números negativos, para indicar que el resultado es un número negativo se debe mostrar realizando un parpadeo del mismo en positivo en los LEDS cada 300ms.
4. El sistema debe informar que el resultado no se puede visualizar en el caso que sobrepase los 16Bits de los LEDS haciendo parpadear todos los LEDS cada 1000ms.
5. Límites del sistema:
 * Número mínimo para ingresar: 0
 * Número máximo para ingresar: 65535
 * Rango de números para el resultado: -65535 y 65535
### Materials:
1. Microcontrolador STM32F103
2. 16 LEDS ubicados en línea.
3. 6 pulsadores
3. Programador.
4. Resistencias varias.
