Stochastic process is used to model phenomena in finance.
Quantities that of focus  - Stock prices, Interest rates and their volatilities.
Evolution of such a process is governed by a Stochastic differential equations. and such models aims to solve the SDEs for the expectation value of a certain random variable of interest.

- Analytical solutions for solving SDEs  - solving Black-Scholes equation for European options.
- Numerical Approach:
  - Monte Carlo Integration (MCI)
    - Corresponding quantum approach -> [QAE]([[2012.03819v3] A Threshold for Quantum Advantage in Derivative Pricing](https://arxiv.org/abs/2012.03819v3)) 
    - There are other variants to this approach like the work done by Cornelissen and Jerbi, where they solved this problem with the framework of markov reward processes.
    - for the state preparation one can look into Grover-Rudolph algorithm for loading efficiently integrable distributions. (however classical MCI are used to integrate the distribution which affects the quantum advantage of the QMCI hence this is not a suitable state preparation technique)
      - other variational methods one can consider is Geometric brownian motion.
	- Need to look other non unitary approaches for state preparation techniques.
  - Numerical solution for Differential equations:
    - The theory comes from the Feynman-Kac formula: the expectation of certain random variables, whose evolution is described by SDEs, can be formulated as the solution to parabolic partial differential equations (PDEs).
    - Classical approaches for solving well know Black-Scholes PDE, are finite difference method (FDM) , finite volume method (FVM), finite element method (FEM). and there are other spectral method one could explore.
    - Quantum approaches primarily follow solving the Quantum Linear solvers(QLS) and QLSAs.
      - Then one could survey the following literatures:
    - There are Variational algorithms that have been studied well for these problems: such as Wick-rotated schrodinger equation with an imaginary time variable and then using Variation quantum imaginary time evolution.
    - Another approach by Lubasch: a variational circuit is built to construct the quantum state representing the solution of the PDE in an amplitude encoding.
    - There are other approaches by Kyriienko.

Financial Applications:
- with the quantum algorithms discussed above one could look into application of stochastic modelling in finance.
  - Derivative Pricing: 
  - Risk modelling