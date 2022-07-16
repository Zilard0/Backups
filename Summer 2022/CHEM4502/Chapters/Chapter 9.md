---
tags: 🧠️/📝️/👨‍🏫/📥️
publish: true
aliases: 
---
# Chapter 9
Created:  [[2022-07-12]]

## Concepts
* LCAO-MO: a means of using atomic orbitals (on different atoms) to construct MOs for the entire molecule; provide approximate solutions to the Schrodinger equation
* Overlap Integral: The degree to which atomic wavefunctions share a portion of the 3-d space
* Coulomb Integral: Used to calculate the classical electrostatic interaction energies among charged particles
* Exchange integral: Purely QM effect with unknown interpretation-but provide the net energy to make the bonding favorable.


## Notes
### Hamiltonian for a Molecule
* Can be written by considering all electrostatic interactions
* The Born-Oppenheimer approximation suggests that we can often safely ignore the KE of any/all nuclei
* Multi-electron systems are still a problem; we use $H^{+}_{2}$ as a solvable, one electron model system for molecules
![[Pasted image 20220716083217.png|500]]


### Born-Oppenheimer approximation
* Nuclei move slow compared to electrons, so we assume they are fixed in space
* R is a parameter
* Wavefunctions obtained are not exact, but can be improved iteratively

### Molecular Orbital (MO) Theory
* Used to construct molecular wavefunctions 
* similar to the development of H atomic wavefunctions 
* $H^{+}_{2}$ used as a model; solutions are not chemically insightful and are generally not used
* Simplest system:  $H^{+}_{2}$
	* Only one electron; can be solved exactly if using B-O approximation

	* LCAO-MOs
		* $\psi_{+}=c_{1}\phi_{1s,A}+c_{2}\phi_{1s,B}$
		* $\psi_{+}=c_{1}\phi_{1s,A}-c_{2}\phi_{1s,B}$
	* Energy of Wavefunction:
	* $$E=\frac{\int\psi^{*}\hat H\psi dr}{\int\psi^{*}\psi dr}$$
* $E_{+}$ is more stable than separated fragments, leads to chemical bond
* $E_{+}$ is more stable than separated fragments, leads to chemical bond

### Types of MOs
* $\sigma$: contains electron density on the internuclear axis
* $\pi$: contains one nodal plane inclusive of internuclear axis
* $\delta$: contains two nodal planes inclusive of the internuclear axis
* Bonding: Has no nodal planes perpendicular to the bond axis and between the nuclei
* Antibonding: Has at least one nodal plane perpendicular to the bond axis and between the nuclei
* Nonbonding: Do not have AO contributions from both adjacent atoms
![[2022-07-16 08-02-18.excalidraw]]

### MO electron configurations of diatomic molecules
* Written based on possible MOs
	* Predict bond orders and bond stability, along with trends in bond energy and length

* Molecular term symbols
	* Similar to atomic term symbols, but for molecules
	* Hund's rules apply to molecules too
	* We generally determine only the lowest energy molecular term for a given configuration


## Chapter 9 Equations
### Hamiltonian for $H^{+}_{2}$ 
$$\hat H_{H^{+}_{2}}=\frac{-\hbar^{2}}{2m_{e}}\nabla^{2}-\frac{e^{2}}{4\pi \epsilon_{o}}\left( \frac{1}{r_{A}}+\frac{1}{r_{B}}-\frac{1}{R}\right)$$

### Energy of a wavefunction
$$E=\frac{\int\psi^{*}\hat H\psi dr}{\int\psi^{*}\psi dr}$$
### Energies of 1s-based bonding & anti-bonding in $H^{+}_{2}$
$$E_{\pm}=E_{1s}+\underbrace{\frac{J \pm K}{1\pm S}}_{\text{QM Bonding Energy}}$$
* $K$: Exchange Integral
* $J$: Coulomb Integral
* $S$: Overlap Integral

### Overlap Integral
Use: Measure extent to which wavefunctions share a space
$$S=\int_{\text{All space}}\phi^{*}\phi dr$$
### Coulomb Integral
Use: Accounts for classical electrostatic interactions (Attractions & repulsions between atoms)
$$J=\frac{e^{2}}{4\pi \epsilon_{o}R}-\frac{e^{2}}{4\pi \epsilon_{o}}\int\frac{\phi^{*}_{i}\phi_{i}}{r_{j}}dr$$
### Exchange Integral
Use: Accounts for QM interactions to bond energies
$$K=\frac{Se^{2}}{4 \pi \epsilon_{o}R}-\frac{e^{2}}{4 \pi \epsilon_{o}}\int\frac{\phi^{*}_{i}\phi_{i}}{r_{j}}dr$$
## Figures
### Comparison of Overlap for MOs
![[Pasted image 20220716085543.png|400]]
### Energies vs. Intermolecular separation
![[Pasted image 20220716085830.png|400]]

