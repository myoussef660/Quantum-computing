# Quantum-computing
Quantum State Preparation in Qiskit

This repository explores quantum state preparation using Qiskit, starting from simple examples and gradually building toward more general quantum states.

The goal is to understand how to construct quantum circuits that prepare a desired state from the initial computational basis state (|0\rangle^{\otimes n}).

Overview

The project begins with the simplest case of a single qubit and then moves to two-qubit systems and the general (n)-qubit case. We first focus on states with real and non-negative amplitudes, where the preparation can be understood using rotation gates. We then extend the discussion to states with complex amplitudes by including the appropriate phase information.

Contents

* State preparation for one qubit
* State preparation for two qubits
* Generalization to (n) qubits
* Real non-negative amplitudes
* Complex amplitudes
* Qiskit circuit implementations

Motivation

Quantum state preparation is a basic but important ingredient in quantum algorithms and quantum simulation. Preparing a desired input state allows us to encode classical or physical data into a quantum circuit, which is often the first step before applying a quantum algorithm or simulating quantum dynamics.

Tools

This project uses:

* Python
* Qiskit
* NumPy

Status

This is an exploratory learning project. The code is intended to build intuition step by step, rather than provide an optimized state preparation algorithm.
