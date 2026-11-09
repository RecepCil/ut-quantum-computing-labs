# ut-quantum-computing-labs

Programming lab homework for **LTFY.04.012 Fundamentals of Quantum Computing: Theory and Practice**
(University of Tartu), written in Python with [Qiskit](https://qiskit.org/).

## Homework

| # | Notebook | Topic |
|---|----------|-------|
| 1 | [`homework/01_ry_rotation_z_average.ipynb`](homework/01_ry_rotation_z_average.ipynb) | Start in \|0⟩, apply R_y(θ) for 20 equally spaced θ in [0, 2π), measure with 2048 shots on `AerSimulator`, and plot the average of Z against θ. |
| 2 | [`homework/02_zz_average_two_qubits.ipynb`](homework/02_zz_average_two_qubits.ipynb) | Two-qubit parameterized circuit (R_y and CNOT layers) over a 20×20 grid of (α, β) in [0, 2π)², measure with 1024 shots on `AerSimulator`, and plot the average of Z⊗Z as a 3D surface. |

## Running

```bash
pip install qiskit qiskit-aer matplotlib pylatexenc jupyter
jupyter notebook homework/
```
