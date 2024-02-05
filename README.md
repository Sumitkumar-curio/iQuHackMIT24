# Quantum Tanh Approximation Challenge

This repository contains my solution for the Quantum Tanh Approximation Challenge on the Classiq platform.

## Challenge Overview

In this challenge, the goal is to design the most accurate approximation for the tanh(x) function using polynomial approximations in the domain [0, 1). The challenge consists of two stages:

### Stage 1

- **Objective:** Design the most accurate approximation with the lowest maximal distance between the solution and the ground truth.
- **Constraints:**
  - Maximum circuit width: 30 qubits.
  - Maximum circuit depth: 3,000.

### Stage 2

- **Objective:** Design the most efficient algorithm with the highest precision possible.
- **Constraints:**
  - Maximum circuit width: 100 qubits.
  - Maximum circuit depth: 30,000.

## Quantum Model

The quantum model is implemented using the Classiq platform. The core quantum function is defined as follows:

```python
@QFunc
def compute_tanh(precision: QParam[int], x: QNum, tanh_x: Output[QNum]):
    # Quantum implementation goes here
    pass
