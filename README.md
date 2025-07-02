# Quantum-multicontrolled-U
This implements a multi-controlled U gate in Qiskit using only single qubit gates and CNOT gates. One key technique used is the Gidney-Jones temporary logical AND gadget. This enables us to have the gate depth be O(log_2(n)). The number of ancillas needed however is O(n), as is the number of gates.

A number of functions and circuits are implemented as part of this process. First, there is an implementation of the AND gadget. Then, there is an implementation of a single controlled U gate, and then there is an inductive implementation of a multicontrolled U gate. These constructions take the standard inputs, theta, phi, lambda, and alpha, which have the same meanings as in the Qiskit implementation of controlled U gates.
