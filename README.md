# Optimizing Resource Allocation in Quantum Networks through Game Theory

This repository contains the simulation code and data for the paper "Optimizing Resource Allocation in Quantum Networks through Game Theory." The study explores a novel resource allocation strategy using quantum game theory principles to enhance the performance of quantum networks.

## Overview

Quantum game theory integrates quantum mechanics with classical game theory, providing advanced strategies for resource management in quantum networks. This project simulates the allocation of entanglement resources among quantum nodes (qubits) using a game-theoretic approach.

## Features

- **Quantum Circuit Simulation**: Utilizes Qiskit to simulate entanglement and measurement processes.
- **Resource Allocation Algorithm**: Implements a dynamic allocation strategy based on game outcomes.
- **Convergence Analysis**: Evaluates algorithm performance across different numbers of qubits.

## Requirements

- Python 3.x
- Qiskit
- Matplotlib
- NumPy

## Installation

```bash
pip install matplotlib qiskit qiskit_aer numpy
```

## Usage

### Simulate Resource Allocation
Run the `quantum_game_theory_resource_allocation` function with desired parameters to simulate resource distribution.

### Evaluate Performance
Use `evaluate_for_qubits` to analyze resource allocation across various qubit counts.

### Visualize Results
Generate plots to visualize resource distribution patterns.

## Parameters

- **E**: Total available entanglement (default: 100)
- **S**: Strategy set for nodes (e.g., ['S1', 'S2', 'S3'])
- **maxIterations**: Maximum number of iterations for convergence (default: 1000)
- **epsilon**: Convergence threshold (default: 0.01)

## Results

The algorithm demonstrates a consistent inverse relationship between the number of qubits and resources allocated per node. As the number of nodes increases, the resources allocated per node decrease proportionally, ensuring equitable distribution.


## Contribution

Contributions are welcome! Please fork this repository and submit pull requests for any enhancements or bug fixes.

## License

This project is licensed under the MIT License.

## Contact

For questions or further information, please contact: Kushagra Agrawal - kush4409@gmail.com
