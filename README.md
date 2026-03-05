# Implementación de Autómata Finito

## Sistema Operativo
Windows 11

## Lenguaje de Programación
Java

## Herramientas Utilizadas
- Java 
- Online GDB
- Terminal o Símbolo del sistema

# Instrucciones para ejecutar el programa

1. Guardar el archivo con el nombre "Automata.java".

2. Abrir una terminal o consola en la carpeta donde está el archivo.

3. Compilar el programa con el siguiente comando:

javac Automata.java

4. Ejecutar el programa con el comando:

java Automata

5. El programa solicitará ingresar una cadena compuesta por los símbolos "a" y "b".

Ejemplo de entrada:

Ingrese la cadena: ab

6. El programa indicará si la cadena es ACEPTADA o RECHAZADA según el autómata implementado.

# Explicación del algoritmo

El programa implementa un autómata finito determinista (AFD).

El autómata procesa una cadena de entrada símbolo por símbolo.  
Para cada símbolo leído, el programa verifica en qué estado se encuentra actualmente y determina el siguiente estado según las transiciones definidas por el autómata.

El programa inicia en el estado inicial 0137.

Durante la ejecución:
- Si el símbolo leído es "a" o "b", el programa cambia al estado correspondiente según las reglas de transición.
- Este proceso se repite hasta que se hayan leído todos los símbolos de la cadena.

Al finalizar el procesamiento de la cadena, el programa verifica si el estado final corresponde a uno de los **estados de aceptación**.

Si el estado final es 247, 68, 8 o 58, la cadena es aceptada.  
En caso contrario, la cadena es rechazada.

---

# Autor
Trabajo realizado por Maybeth López Bedoya y Nash Díaz Quessep.
