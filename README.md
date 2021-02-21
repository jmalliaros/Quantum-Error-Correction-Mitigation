# Quantum-Error-Correction-Mitigation
Basic error correction is explored for dealing with bit flip and phase flip errors in a circuit that prepares a bell state. After the 9-qubit Shor [9,1,3] code is implemented to correct phase and bit flip errors, a noise mitigation technique is explored using a simulated depolarizing noise model and real hardware.

## Dependencies
qiskit v0.19.1

To install qiskit
```
pip install qiskit
```
or update with
```
pip install qiskit -U
```

This is the 9-qubit Shor [9,1,3] code, used to encode one logical qubit. In this project, we apply two of these codes to create two logical qubits on an ideal system. 
<img src="https://github.com/jmalliaros/Quantum-Error-Correction-Mitigation/blob/main/shorcode.png" width="800">

Here are the results from noise mitigation on both a simulated depolarizing noise model and the ibmq_belem 5 qubit, quantum volume of 16 superconducting device. 
<img src="https://github.com/jmalliaros/Quantum-Error-Correction-Mitigation/blob/main/noise-mit-plot.PNG" width="800">




