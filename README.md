# Finite Automata Implementation

## Operating System
Windows 11

## Programming Language
Java (JDK 17 or later)

## Tools Used
- Java JDK
- Visual Studio Code / IntelliJ IDEA (optional)
- Terminal or Command Prompt

---

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

---

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

---

# Author
Student implementation for the course **Formal Languages – EAFIT University**.
