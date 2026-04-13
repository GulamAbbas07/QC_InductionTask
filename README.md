# Task-1
**Quantum Entanglement Simulation using Qiskit**  

**Overview**
<br>
This project demonstrates a basic quantum computing concept — quantum entanglement — using the Qiskit framework.
<br>
A 2-qubit quantum circuit is created, entangled using a Hadamard and CNOT gate, and then simulated using AerSimulator. The results are measured and visualized using a histogram.  

**Technologies Used**
<br>
Python
<br>
Qiskit
<br>
Qiskit Aer Simulator  


**Concept**
<br>
The circuit creates a Bell State, which is one of the simplest examples of quantum entanglement:
<br>
Applying a Hadamard gate (H) to the first qubit creates superposition.
<br>
Applying a CNOT gate (CX) as first qubit as control and second qubit as target that entangles the two qubits.
<br>
Measuring both qubits produces correlated results.
<br>
<br>
**Expected output:**
<br>
Only 00 and 11 states appear with ~50% probability each.
<br>
<br>
# Task-2
**Grover's Algorithm (3 Qubits) using Qiskit**  

**Overview**
<br>
This project implements Grover's Search Algorithm using Qiskit for a 3-qubit system.
<br>
Grover’s algorithm is a quantum algorithm that provides a quadratic speedup for searching an unsorted database. In this implementation:
<br>
A random target state is selected.
<br>
The oracle marks the target.
<br>
The diffusion operator amplifies its probability.
<br>
The result is measured and visualized.  

**Technologies Used**
<br>
Python
<br>
Qiskit
<br>
Qiskit Aer Simulator  

**Grover’s algorithm consists of:**
<br>
***Initialization***
<br>
Apply Hadamard gates to create superposition.
<br>
***Oracle***
<br>
Marks the correct solution (phase inversion).
<br>
***Diffusion Operator***
<br>
Amplifies the probability of the marked state.
<br>
***Iteration***
<br>
Repeat steps to maximize success probability.
<br>
***Measurement***
<br>
Observe the most probable state.
