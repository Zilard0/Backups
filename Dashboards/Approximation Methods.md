---
tags: 🧠️/📝️/👨‍🏫/📥️
publish: true
aliases: 
---
# Approximation Methods
Created: ### [[2022-07-14]]
___
## Concepts
- **Basis Function**: A function used as a component for a trial wavefunction
- **Basis set**: The set of all basis functions used to construct a trial wavefunction

## Notes
### The Variational principle:
* Use: Provides a way of setting an upper limit on the approximated energy of a quantum system. However, we are only concerned with the minima due nature preferring minima
* Provide one or more optimizable parameters are being used here.
	- The energy can be improved with a better model wavefunction
	- the $N\times N$ secular determinant gives N energies, one for each unique MO wavefunction

### Basic Approach to Variational Principle Calculations
- Select a basis set (Or N basis functions)
- Calculate all possible $H_{ij}$ and $S_{ij}$ integrals (Minimum $N^{2}$ integrals)
- Find N values of E from the secular determinant
- Find the $c_{i}$ coefficients for $i$ corresponding to each value of E


### Huckel's Thoery
- Use: Provides a way to estimate the energies of conjugated (Organic) $\pi$ systems
- Considered to be a specific example of approximation in practice
- Assumptions:
	- Basis set: Unhybridized C 2p AOs perpinduclar to plane of molecule
	- Overlap integral: $S_{ij}=\delta_{ij}$ 
	- Resonance Integral:
		- $H_{ii}=\alpha=\text{-IE of }CH_{3}<0$
		- $H_{ij}=\beta=2E_{2p}-E_{\pi}<0$ for adjacent C atoms
		- $H_{ij}=0$ for non-adjacent C atoms 
	- Resonance Energy: a comparison of the $\pi$ energy of a conjugated system to that of ethylene. $E=2\alpha+2\beta$ for ethylene (2 electrons)
	 
### Basis Sets
- Collections of functions sued to represent AO wavefunctions for building LCAO-MOs 
- Usually composed of Gaussian functions, either alone or more commonly themselves linearly combined
- Core and valence AOs are typically modeled differently; in some basis sets, the core AOs are even modeled as a group
- Additional types of functions (i.e. diffuse and polarization) can be added to the bass set as desired
- Increasing the size of the basis set should lower the varitational energy


### Modern Implementations
- Hartree-Fock self-consistent field (SCF) methods:
	- Model electron clouds using averaged electron densities, with teh final solution achieved iteratively
- Semi-empirical: Use pre-defined integrals and basis sets to reduce requisite calculations; solutions are quicker but lower quality
- Perturbation theory: A solvable model is used as a starting point, with additional terms added to estimate differences between the model and the real complicated system
- MCSCF: SCF Calculations are performed for different electron configurations, and the results are themselves linearly combined; CI is MCSCF with all configuration considered
- CC: Similar to MCSCF, but formulated in a different and more reliable way
- Density functional theory: Fundamentally different than other methods, but in practice done in much the same way; based on electron density (rather than AOs) and not inherently flawed (But error-inducing approximations must still be made)

- **Note that one should always compare approximated results to known (preferably experimental) results as a test of quality**


## Eqns

### Trial Wavefunction
Use: Linear combination of simpler functions
$$\psi =\sum\limits_{i}c_{i}\phi_{i}$$
- $\phi_{i}$=Basis set (Collection of basis functions)
- $c_{i}$= Scales functions


### Variational Equation
Use: Approximated energies are always the upper limits to the real energy, and are calculated according the formula above:
$$E_{0}\leq \frac{\int\psi_{i}\hat H \psi_{i}dr}{\int\psi_{0}^{2}dr}$$
### The Secular Equation
Use: Relates the coefficients of trial wavefunctions to their energies

$$\sum\limits_{i=1}^{N}c_{i}(H_{ij}-ES_{ij})=0$$

- Determinant Format: 
$$
\begin{vmatrix}H_{11}-ES_{11}  & H_{12}-ES_{12} & \dots & H_{1N}-ES_{1N} \\ H_{21}-ES_{21} & H_{22}-ES_{22} & \dots \\ \vdots & \vdots & \ddots \\ H_{N1}-ES_{N1} &  &  & H_{NN}-ES_{NN}\end{vmatrix}=0
$$



### Perturbational Energies Eqn
Use: Calculated from unperturbed wavefunction and is a correction to Hamiltonian
$$E^{(1)}=\int \psi^{\star (0)} \hat H^{(1)} \psi^{(0)}$$

### Hartree Product Wavefunction Eqn
Use: The total wavefunction for a system is the product of the individual wavefunctions within it.
$$\Psi_{HP}=\phi_{1}\phi_{2}\dots \phi_{N}$$

### Hamiltonian of Entire System Using Hartree-Fock Methods Eqn
Use: The Hamiltonian of the entire system is the sum of one-electron Hamiltonian, which themselves describe an electon interacting with all nuclei and an average field from the other electrons
$$\hat H=\sum\limits_{i=1}^{N}f_{i}$$
$$f_{i}=-\frac{1}{2}\nabla_{i}^{2}-\sum\limits_{k=1}^{M}\frac{Z_{k}}{r_{ik}}+V_{i}\{j\}$$
