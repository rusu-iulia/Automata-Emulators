# Automata Emulators
Python lab project for CS112 – Formal Languages and Automata, simulating different automata and a Turing Machine.
## Overview
This project consists of some automata and formal languages concepts and implementations from this semester:
- Deterministic Finite Automata (DFA)
- Non-deterministic Finite Automata (NFA)
- Pushdown Automata (PDA)
- Turing Machine 

## Features
- DFA Emulator: Processes an input string using a deterministic approach
- NFA Emulator: Processes an input string using a non-deterministic approach (with epsilon transitions)
- PDA Emulator: Processes an input string by simulating a pushdown automata (with stack operations)
- Turing Machine: Processes an input string using a basic Turing machine

## Implementation Details
Every folder consists of the python file and its corresponding text file, and it is reusing the work from previous laboratories.

## Functions
- `load_automata()` and `save_automata()` : Reads automata configuration from file and saves it into a file
- `dfa_emulator()` : Simulates a DFA Emulator
- `epsilon_closure()` and `nfa_emulator()`: Computes epsilon closure (finds the states that are reachable from a state P using epsilon transitions) and simulates a NFA Emulator
- `pda_emulator()` : Simulates a PDA Emulator
- `Turing_machine()` : Simulates a Turing machine that adds two unary numbers

## Conclusion

This project demonstrates practical implementations of key concepts from CS112 – Formal Languages and Automata. By simulating DFA, NFA, PDA, and Turing Machines in Python, it provides:
- Hands-on experience with automata theory 
- Understanding of stack operations, epsilon transitions, and Turing computations
- A foundation for more advanced computation theory projects
  
It’s a complete, modular toolkit for exploring and experimenting with different types of automata.
