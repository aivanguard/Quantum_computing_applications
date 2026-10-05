# Quantum_computing_applications
Running algorithms for optimization use cases that employ Variational Quantum Eigensolver (VQE) and financial QAOA to name a few

Use cases in chemistry, physics and finance are easily demonstrated  using Quantum computing  frameworks, such as Pennylane AI and IBM Qiskit. The back end compute infrastructure for these problems will use hybrid classical ML for the training stage  and run with quantum computing processors for the VQE algorithm.

In the case of the portfolio optimization when the number of securities increase to a large value, VQE is used for obtaining quantum advantage. Using VQE, portfolio constraints (like budget) are injected as penalty terms, formulating it into a Quadratic Unconstrained Binary Optimization (QUBO) problem. With the QUBO solution the hybrid classical quantum optimization job  can disregard the highly correlated stocks from the final selection based on the risk factor setting. Also, low variance and lower correlation between the stock tickers are favored based on the test of the data with the chosen assets
