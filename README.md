# VQE
Variational Quantum EigenSolver

Built an Variational Quantum Eigensolver which can find the minimum eigen value of a 4x4 Hermitian Matrix.

Use: Finding the ground state of a molecule

Steps Involved:

Step 1: Decomposition of the Hamiltonian(Hermitian Matrix) into Pauli Matrices
Step 2: Guessing an ansatz
Step 3: Changing into Z basis and measuring.

Step 2 and Step 3 are run iteratively so get to the lowest value which is the lowest eigen value.
