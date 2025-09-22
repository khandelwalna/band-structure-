# band-structure-

to calculate band structure  using quantum algorithms we need hamiltonian to get energy eigenvalues.

step1: you have to calculate the hopping parameters and energy values using wannier90 software 
step2: extract hamiltonian from the files 
step3: change Hamiltonian  in pauli basis
step4: now calculate ground state energy value using variational quantum eigensolver 
step5: calculate higher states using variational quantum deflation algorithm 
step6: plotting 

qiskit_version = 0.41.0
python= 3.18.0
tbmodels= 1.4.3
qiskit_aer = 0.11.0
qiskit_algorithms = 0.3.0
