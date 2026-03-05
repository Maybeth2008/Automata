(Inglés)
# Finite Automata Implementation

## Operating System
Windows 11

## Programming Language
Java (JDK 17 or later)

## Tools Used
- Java JDK
- Visual Studio Code / IntelliJ IDEA (optional)
- Terminal or Command Prompt

# How to Run the Program

1. Save the file as `Automata.java`.

2. Open a terminal in the folder where the file is located.

3. Compile the program with:

javac Automata.java

4. Run the program with:

java Automata

5. The program will ask you to enter a string composed of the symbols **a** and **b**.

Example:

Enter the string: ab

6. The program will print whether the string is **ACCEPTED** or **REJECTED** according to the finite automaton.

# Algorithm Explanation

This program simulates a deterministic finite automaton (DFA).

The automaton reads the input string symbol by symbol.  
For each symbol, the program checks the current state and determines the next state based on the transition rules defined by the automaton.

The program starts in the initial state **0137**.

During execution:
- If the symbol is **a** or **b**, the program moves to a new state according to the transition function.
- This process continues until all symbols of the string are processed.

After processing the entire string, the program checks if the final state belongs to the set of accepting states.

If the final state is **247** or **58**, the string is accepted.  
Otherwise, the string is rejected.

# Author
Student implementation for the course **Formal Languages – EAFIT University**.


(Español)
# Implementación de Autómata Finito

## Sistema Operativo
Windows 11

## Lenguaje de Programación
Java (JDK 17 o superior)

## Herramientas Utilizadas
- Java JDK
- Visual Studio Code / IntelliJ IDEA (opcional)
- Terminal o Símbolo del sistema

---

# Instrucciones para ejecutar el programa

1. Guardar el archivo con el nombre `Automata.java`.

2. Abrir una terminal o consola en la carpeta donde está el archivo.

3. Compilar el programa con el siguiente comando:

javac Automata.java

4. Ejecutar el programa con el comando:

java Automata

5. El programa solicitará ingresar una cadena compuesta por los símbolos **a** y **b**.

Ejemplo de entrada:

Ingrese la cadena: ab

6. El programa indicará si la cadena es **ACEPTADA** o **RECHAZADA** según el autómata implementado.

---

# Explicación del algoritmo

El programa implementa un **autómata finito determinista (AFD)**.

El autómata procesa una cadena de entrada símbolo por símbolo.  
Para cada símbolo leído, el programa verifica en qué estado se encuentra actualmente y determina el siguiente estado según las transiciones definidas por el autómata.

El programa inicia en el estado inicial **0137**.

Durante la ejecución:
- Si el símbolo leído es **a** o **b**, el programa cambia al estado correspondiente según las reglas de transición.
- Este proceso se repite hasta que se hayan leído todos los símbolos de la cadena.

Al finalizar el procesamiento de la cadena, el programa verifica si el estado final corresponde a uno de los **estados de aceptación**.

Si el estado final es **247** o **58**, la cadena es **aceptada**.  
En caso contrario, la cadena es **rechazada**.

---

# Autor
Trabajo realizado para la asignatura **Lenguajes Formales – Universidad EAFIT**.
