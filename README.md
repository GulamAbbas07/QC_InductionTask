# Task-1
Quantum Entanglement Simulation using Qiskit
**Overview**
<br>
This project demonstrates a basic quantum computing concept — quantum entanglement — using the Qiskit framework.
A 2-qubit quantum circuit is created, entangled using a Hadamard and CNOT gate, and then simulated using AerSimulator. The results are measured and visualized using a histogram.
<br>
**Technologies Used**
Python
Qiskit
Qiskit Aer Simulator
Matplotlib
<br>
**Concept**
The circuit creates a Bell State, which is one of the simplest examples of quantum entanglement:

Applying a Hadamard gate (H) to the first qubit creates superposition.
Applying a CNOT gate (CX) as first qubit as control and second qubit as target that entangles the two qubits.
Measuring both qubits produces correlated results.
<br>
**Expected output:**
Only 00 and 11 states appear with ~50% probability each.
<br>
<br>
# Task-2
