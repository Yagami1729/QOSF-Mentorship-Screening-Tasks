# QOSF-Mentorship-Screening-Task 2
- Prepare 4 random 4-qubit quantum states of your choice
- Create and train a variational circuit that transforms input states into predefined output states. Namely
    - if random state 1 is provided, it returns state |0011>
    - if random state 2 is provided, it returns state |0101>
    - if random state 3 is provided, it returns state |1010>
    - if random state 4 is provided, it returns state |1100>
- What would happen if you provided a different state?

Analyze and discuss the results.

Feel free to use existing frameworks (e.g. PennyLane, Qiskit) for creating and training the circuits.
This PennyLane demo can be useful: Training a quantum circuit with Pytorch, 
This Quantum Tensorflow tutorial can be useful: Training a quantum circuit with Tensorflow .

For the variational circuit, you can try any circuit you want. You can start from one with a layer of RX, RY and CNOTs, repeated a couple of times (though there are certainly better circuits to achieve this goal). 
