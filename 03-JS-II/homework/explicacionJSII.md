Ciclo for:
Los ciclos o bucles nos ayudan a ejecutar un mismo bloque de código muchas veces.
EL ciclo o bucle for, es el más simple. 
Se declara en 3 partes:
1 - Instruccion inicial: donde declaramos una variable que vaos a necesitar dentro del ciclo, se ejecuta antes de iniciar el ciclo.
2 - Una condicion: dice cuando el ciclo va a terminar. Mientras evalue true, continúa, y cuando evalue false, termina. Esta condición se declara con una expresion booleana.
3 - La instruccion de cada iteracion (o repetición): se ejecutará al final de cada iteración del ciclo.
Cada ejecución del bloque de código es una iteración.
EJ: for (var i = 0; i <= 5; i++ )

OPERADORES LOGICOS
&& o AND: convierte valores en booleanos y los compara, busca el primer valor falso, si no lo encuentra retorna el valor verdadero. Esto quiere decir: Si los valores a comparar, de la derecha y de la izquiera del operador, son verdaderos (2 === 2 && 3 === 3) retornara verdadero. si uno es falso (2 === 2 && 3 === 5) retornara falso. Y si ambos son falsos retornara falso.
|| o OR: Retorna un valor veraddero si al menos un valor es verdadero y retornara falso, si ningun valor es verdadero. cuando encuentra un valor verdadero, no seguirá evaluando.
! o NOT: Convierte la expresion a su valor booleano y despues lo invierte.Es decir, da falso lo verdadero y verdadero lo falso.