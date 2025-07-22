## Description

**Unlocking the potential of quantum computing for clean water technologies**

This work simulates a minimal graphene-oxide membrane interacting with sodium and water molecules (C4O2H4 + Na(H2O)) to investigate its suitability for desalination. By combining classical electronic structure methods (ASE → PySCF) with quantum algorithms (Qiskit Nature → VQE), it extracts accurate active-space Hamiltonians and computes ground-state energies using variational quantum eigensolvers (VQE). By comparing the VQE result to the exact ground‑state energy, it offers a powerful framework for exploring and optimizing water desalination membranes at the quantum level.

Key steps include:

- **Geometry preparation** with ASE and PySCF.
- **Mean‑field calculation and optimization** using RKS and Berny.
- **Active‑space selection, integral generation, and export** to HDF5.
- **Quantum problem setup** and mapping of molecular Hamiltonians to qubit operators.
- **Ansatz design and VQE execution**: optimize parametrized circuit for minimum energy.
- **Result analysis**: compare VQE and exact ground‑state energies to assess performance.
