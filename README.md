# Ciclo_Basico_De_Instruciones
El siguiente trabajo tiene la finalidad de presentar una simulación del ciclo básico de instrucciones intentando imitar 
la ejecución de los procesos en un sistema operativo. Para ello, las serie de instrucciones estarán almacenadas en un archivo de texto (.txt) 
y tendrá una salida de la misma manera.

**IMPORTANTE:**
Si deaseas cambiar el archivo de entrada, modifica la linea 35. Donde dice 'ENTRADA3.txt' escribe el titulo del documento txt que deseas
que se tome como entrada. 
Ten en cuenta, de que esto es un ciclo basico de instruciones, por lo que cada linea sera una instruccion.

**Instruciones por las que puedes optar**

SET - MEM - SET D1 X NULL NULL, Almacena el valor X en la dirección de memoria D1. donde X es un valor inmediato, directo o constante. 
Cuando se lee la instrucción SET el valor X se almacena en Memoria sin ejecución del procesador.
ADD - AÑADIR - Hay tres formas: ADD D1 NULL NULL, añade el valor de la dirección de memoria D1 al valor cargado en el registro acumulador. 
ADD D1 D3 NULL Carga el valor en la dirección de memoria D1 en el registro acumulador y lo suma al valor encontrado en la dirección de memoria D3. 
ADD D1 D3 D4 igual que ADD D1 D3 pero pone el resultado en D4.
SUB - SUBTRACTION - Hay tres formas: SUB D1 NULL NULL, SUB D1 D2 NULL y SUB D3 D2 D1 similar a ADD pero realiza la resta.
MUL - MULTIPLICACIÓN - Usando ADD realiza la operación de multiplicación. Hay tres formas: MUL D1 NULL NULL, MUL D1 D2 NULL, MUL D1 D2 D3 similar a ADD y SUB. 
La multiplicación no se puede utilizar con un valor inmediato/directo/constante.
INC - INCREMENT - INC D3 NULL NULL Carga el valor en la dirección de memoria D3 suma 1 y almacena en la misma dirección.
DEC - DECREMENT - DEC D3 NULL NULL Carga el valor en la dirección de memoria D3 suma 1 y almacena en la misma dirección
MOV - MOVE - MOV D2 D10 NULL Carga el valor en la dirección de memoria D2 a la dirección de memoria D10 y borra la dirección D2
LDR - LOAD - LDR D3 NULL NULL Carga el valor en la dirección de memoria D3 y lo pone en el registro acumulador
STR - STORE - STR D3 NULL NULL Lee el valor en el registro acumulador y lo pone en la dirección de memoria D3
BEQ - EQUAL - BEQ D10 NULL NULL Carga el valor en la dirección de memoria D10 si la resta con los valores del registro acumulador es cero y lo pone en la
dirección de memoria D10. Hay tres formas: BEQ D10 NULL NULL, BEQ D1 D10 NULL, BEQ D1 D2 D3
SHW - SHOW - SHW D2 NULL NULL muestra el valor en la dirección de memoria D2, SHW ACC muestra el valor en el registro acumulador, SHW ICR muestra el valor en el
registro ICR, SHW MAR muestra el valor en el registro MAR, SHW MDR muestra el valor en el registro MDR, SHW UC muestra el valor en la Unidad de Control.
END - INSTRUCCIÓN DE FIN DE LECTURA

**Contactos**
         **@authors**                                      **@emails**
      Sarah Alexandra Cardinaux            -  sarah.cardinaux@correounivalle.edu.co
      Santiago Abihatar Jimenez            -  santiago.abihatar.jimenez@correounivalle.edu.co
      Diana Marcela Sarmiento              -  diana.sarmiento@correounivalle.edu.co 
      Jhon Frank Vasquez                   -  jhon.frank.vasquez@correounivalle.edu.co 
