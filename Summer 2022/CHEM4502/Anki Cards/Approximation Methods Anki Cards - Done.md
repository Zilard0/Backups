## Concepts

START
Basic-lesson
Front: 
Define Basis Function
Back: 
A function used as a component for a trial wavefunction
Extra1:

Extra2:

Lesson: Approximation Methods
Course: CHEM4502
<!--ID: 1658631679885-->
END

START
Basic-lesson
Front: 
Define Basis set
Back: 
The set of all basis functions used to construct a trial wavefunction
Extra1:

Extra2:

Lesson: Approximation Methods
Course: CHEM4502
<!--ID: 1658631679891-->
END

START
Basic-lesson
Front: 
### The Variational Principle Approximation Method
Back: 
Use: Provides a way of setting an upper limit on the approximated energy of a quantum system. However, we are only concerned with the minima due nature preferring minima
Extra1:
- Provide one or more optimizable parameters are being used here.
	- The energy can be improved with a better model wavefunction
	- the $N\times N$ secular determinant gives N energies, one for each unique MO wavefunction
Extra2:

Lesson: Approximation Methods
Course: CHEM4502
<!--ID: 1658631679894-->
END

START
Basic-lesson
Front: 
### Basic Approach to Variational Principle Calculations
Back: 
1. Select a basis set (Or N basis functions)
2. Calculate all possible $H_{ij}$ and $S_{ij}$ integrals (Minimum $N^{2}$ integrals)
3. Find N values of E from the secular determinant
4. Find the $c_{i}$ coefficients for $i$ corresponding to each value of E
Extra1:

Extra2:

Lesson: Approximation Methods
Course: CHEM4502
<!--ID: 1658631679899-->
END

START
Basic-lesson
Front: 
### Huckel's Theory Approximation Method
Back: 
Use: Provides a way to estimate the energy of conjugated (Organic) $\pi$ systems
Extra1:
Assumptions:
	- Basis set: Unhybridized C 2p AOs perpinduclar to plane of molecule
	- Overlap integral: $S_{ij}=\delta_{ij}$ 
	- Resonance Integral:
		- $H_{ii}=\alpha=\text{-IE of }CH_{3}<0$
		- $H_{ij}=\beta=2E_{2p}-E_{\pi}<0$ for adjacent C atoms
		- $H_{ij}=0$ for non-adjacent C atoms 
	- Resonance Energy: a comparison of the $\pi$ energy of a conjugated system to that of ethylene. $E=2\alpha+2\beta$ for ethylene (2 electrons)
Extra2:

Lesson: Approximation Methods
Course: CHEM4502
<!--ID: 1658631679903-->
END

START
Basic-lesson
Front: 
### Basis Sets Approximation Method
Back: 
- Definiton: Collections of functions sued to represent AO wavefunctions for building LCAO-MOs.
Extra1:
- Usually composed of Gaussian functions, either alone or more commonly themselves linearly combined
- Core and valence AOs are typically modeled differently; in some basis sets, the core AOs are even modeled as a group
- Additional types of functions (i.e. diffuse and polarization) can be added to the bass set as desired
- Increasing the size of the basis set should lower the varitational energy
Extra2:

Lesson: Approximation Methods
Course: CHEM4502
<!--ID: 1658631679907-->
END

START
Basic-lesson
Front: 
### What are Gaussian Basis Sets?
Back: 
- Predefined set of N functions to model AOs of an atom
- Linear combinations of Gaussian functions
- Parameterized and variationally optimized

Extra1:
- Pure H wavefunctions $\propto e^{-\alpha r}$
- Gaussian functions $e^{-\alpha r^{2}}$; do not model pure H functions very well.
Extra2:
![[Approximation Methods - GTO vs STO.png|400]]

Lesson: Approximation Methods
Course: CHEM4502
<!--ID: 1658631679911-->
END

START
Basic-lesson
Front: 
### What are Contracted Gaussian Functions (CGFS)?
Back: 
- Linear combinations of Gaussian functions are usually used
- Maintain the benefits of GTOs
Extra1:
- Better functions can be constructed from multiple Gaussians (Individual Gaussians are called primitive functions)
- The more Gaussians used, the better; N=3 and N=6 are common
Extra2:
![[Approximation Methods - LC of Gaussian Functions.png|400]]
Lesson: Approximation Methods
Course: CHEM4502
<!--ID: 1658631679915-->
END

START
Basic-lesson
Front: 
### Basics of Single $\zeta$ Basis Sets in Computational Chemistry
Back: 
- Each AO is represented by a single basis function 
- Called minimal basis sets, as they contain the smallest possible number of basis functions

Extra1:
- Since larger is usually better for basis sets, minimal basis sets are rarely used
- STO-mG: minimal basis set, with m primitive per basis function
Extra2:

Lesson: Approximation Methods
Course: CHEM4502
<!--ID: 1658631679919-->
END

START
Basic-lesson
Front: 
### Basics of Multi $\zeta$ Basis Sets in Computational Chemistry
Back: 
- Similar to minimal bases, except (some) AOs are represented by more than one basis function
- Provide greater computational flexibility

Extra1:
- Double $\zeta$ : two basis functions per AO
- Triple $\zeta$ : three basis functions per AO
- A multi $\zeta$ secular determinant is larger than a single $\zeta$ determinant of the same number of primitives, so flexibility comes at the expense of efficiency
Extra2:

Lesson: Approximation Methods
Course: CHEM4502
<!--ID: 1658631679923-->
END

START
Basic-lesson
Front: 
### Basics of Split Valence Basis Sets in Computional Chemistry
Back: 
- Core orbitals: not involved in bonding, chemically "unimportant," represented by a single CGF
- Valence orbitals: chemically important, must be treated more robustly; represented by multi-$\zeta$ functions

Extra1:
- Famous Example: Pople-type basis sets (e.g. 6-31G):
	- Number before dash: Primitives per core function
	- Number of digits after dash: $\zeta$ number
	- Each digit represents number of primitives in each valence CGF
Extra2:

Lesson: Approximation Methods
Course: CHEM4502
<!--ID: 1658631679927-->
END

START
Basic-lesson
Front: 
### Basics of Correlation Consistent Basis Sets (cc-PVXZ) in Computional Chemistry
Back: 
- Have become widely used in recent years
- Pople sets are usually parametrized with HF; cc-PVXZ are parametrized with more sophisticated computational models
Extra1:
- PV indicates polarized valence
- - Split valence in nature; X indicates the valence number (D=2, T=3, Q=4; 5 and 6 are also available)
Extra2:

Lesson: Approximation Methods
Course: CHEM4502
<!--ID: 1658631679932-->
END

START
Basic-lesson
Front: 
### Basics of Effective Core Potentials (ECPs) In Computational Chemistry
Back: 
- Heavy elements have many electrons, and are hard/time-consuming to treat
- ECPs use simple functions to model electrostatic potentials generated by a nucleus and a number of core electrons


Extra1:
- ECP basis sets are smaller because core electrons are not included
- The core electrons replaced are often problematic, and removing them from a calculation is beneficial
Extra2:
- Types of ECPs
	- Large core ECP: Has explicit functions only for valence electrons
	- Small core ECP: Has explicit functions for valence, n-1 electrons
Lesson: Approximation Methods
Course: CHEM4502
<!--ID: 1658631679936-->
END

START
Basic-lesson
Front: 
### Basics of Polarization Functions in Computational Chemistry
Back: 
- usually consist of $(l+1)$ -type functions
	- Allow electrons to better occupy "empty" spaces, and can therefore be quite important
	
Extra1:
- Can be added to any basis set
		- Pople-type: designated by * or orbital designations (e.g. 6-31G* or 6-31G(d))
		- cc-type: Included in basis set definition
Extra2:

Lesson: Approximation Methods
Course: CHEM4502
<!--ID: 1658631679940-->
END

START
Basic-lesson
Front: 
### Basics of Diffuse Functions in Computational Chemistry
Back: 
- Have relatively large n values, better allow for electron density at a significant distance from the nucleus
- Especially important for large atoms, anions, or other systems with loosely-bound electrons

Extra1:
- Can be added to any basis set
	- Pople-type: designated by + (6-31+G)
	- cc-type: some diffuse functions are already present; additional ones added via aug prefix (aug-cc=PVDZ)
Extra2:

Lesson: Approximation Methods
Course: CHEM4502
<!--ID: 1658631679943-->
END

START
Basic-lesson
Front: 
### Basics of Multiconfigurational SCF (MCSCF or CASSCF) in Computational Chemistry
Back: 
- Considers more than one electron configuration (All possible configs)
- Generates a linear combination of configurations; analogous combining orbitals in MO theory
- Employed by defining an "active space," or a number of electrons and set of orbitals in which they can be distributed

Extra1:
- "CAS" in CASSCF stands for complete active space
- Each configuration is a separate HF Calculation; MCSCF is quite expensive and difficult to employ
Extra2:

Lesson: Approximation Methods
Course: CHEM4502
<!--ID: 1658631679946-->
END

START
Basic-lesson
Front: 
### Basics of Configuration Interaction (CI)
Back: 
- Full CI is MCSCF with all electrons and all orbitals; all configurations are considered
- Full CI is the best calculation we do
- Full CI while theoretically good, is prohibitive to do for all but the smallest molecules

Extra1:
- CI can be truncated:
	- CIS (singles): one electron excitations; not useful for ground states, but useful for excited states
	- CID (doubles): two electron excitations; can be used for ground states
	- CISD: both single and double excitations
Extra2:
- CI methods are not size consistent:
	- CIQ (quadruples) gives different energies than adding two analogous CID calculations
	- Size inconsistency is problematic when using truncated CI
Lesson: Approximation Methods
Course: CHEM4502
<!--ID: 1658631679950-->
END

START
Basic-lesson
Front: 
### Basics of Coupled Cluster (CC) Methods


Back: 
- Related but not identical to CI
- Maintains size consistency

Extra1:
- CC methods
	- CCD: double excitations; implicitly gives $MP \infty$ energies
	- CCSD: singles and doubles
	- CCSDT: includes triple excitations, which are important for accuracy; very expensive
	- CCSD (T): includes simplified triples; is now often used as a gold-standard calculation 
Extra2:
- Is expensive, but can be truncated
Lesson: Approximation Methods
Course: CHEM4502
<!--ID: 1658631679954-->
END

START
Basic-lesson
Front: 
### Basics of Density functional theory (DFT) In Computational Chemistry

Back: 
- Not an ab inition method (HF-based), so there is no guarantee how results will behave
- Based on the electron density (a real quantity), which Kohn and Sham (KS) used to calculate the total energy
- The key feature is the QM exchange-correlation energy ($E_{xc}$), which must ultimately be approximated


Extra1:
- In practice DFT is still done like SCF methods
- Unlike HF, there is no inherent flaw in DFT, so it could be correct
Extra2:
- Many versions of DFT have been developed:
	- All essentially differ in their means of estimating $E_{xc}$
	- Different methods typically have an exchange functional and a correlation functinal; one pairs two to get the full model (e.g. B+LYP=BLYP)
Lesson: Approximation Methods
Course: CHEM4502
<!--ID: 1658631679958-->
END

START
Basic-lesson
Front: 
### Basics of Hybrid Functionals (e.g. B3LYP) in Computational Chemistry 

Back: 
- mix HF exchange with DFT exchange
- Not "pure" DFT, as they employ parameters which are often set

Extra1:
- B3LYP is especially common; it usually strikes a good balance between efficiency/cost and accuracy
Extra2:

Lesson: Approximation Methods
Course: CHEM4502
<!--ID: 1658631679961-->
END

START
Basic-lesson
Front: 
**How does one select an approximation method in Computational Chemistry?**
Back: 
Consider cost and system requirements; desired accuracy; time available; important properties.
Extra1:

Extra2:

Lesson: Approximation Methods
Course: CHEM4502
<!--ID: 1658631679965-->
END

START
Basic-lesson
Front: 
**How does one compare approximation methods in Computational Chemistry?**

Back: 
Many ways; one simple way is to compare results for the ionization energy of He
Extra1:

Extra2:

Lesson: Approximation Methods
Course: CHEM4502
<!--ID: 1658631679969-->
END

START
Basic-lesson
Front: 
**What are Hartree-Fock Self Consistent Field (SCF) Methods?**
Back: 
Model electron clouds using averaged electron densities, with the final solution achieved iteratively
Extra1:

Extra2:

Lesson: Approximation Methods
Course: CHEM4502
<!--ID: 1658631679972-->
END

START
Basic-lesson
Front: 
What does semi-empirical refer to in Approxmation Methods?
Back: 
Using pre-defined integrals and basis sets to reduce requisite calculations; solutions are quicker but lower quality
Extra1:

Extra2:

Lesson: Approximation Methods
Course: CHEM4502
<!--ID: 1658631679976-->
END

START
Basic-lesson
Front: 
What is Perturbation theory in Approximation Methods?
Back: 
A solvable model is used as a starting point, with additional terms added to estimate differences between the model and the real complicated system
Extra1:

Extra2:

Lesson: Approximation Methods
Course: CHEM4502
<!--ID: 1658631679979-->
END

START
Basic-lesson
Front: 
**What is MCSCF in Approximation Methods?**
Back: 
SCF Calculations are performed for different electron configurations, and the results are themselves linearly combined; CI is MCSCF with all configuration considered
Extra1:

Extra2:

Lesson: Approximation Methods
Course: CHEM4502
<!--ID: 1658631679984-->
END

START
Basic-lesson
Front: 
**What is CC in Approximation Methods?**
Back: 
Similar to MCSCF, but formulated in a different and more reliable way
Extra1:

Extra2:

Lesson: Approximation Methods
Course: CHEM4502
<!--ID: 1658631679988-->
END

START
Basic-lesson
Front: 
**What is Density functional theory (DFT) in Approximation Methods?**
Back: 
Fundamentally different than other methods, but in practice done in much the same way; based on electron density (rather than AOs) and not inherently flawed (But error-inducing approximations must still be made)
Extra1:

Extra2:

Lesson: Approximation Methods
Course: CHEM4502
<!--ID: 1658631679991-->
END

START
Basic-lesson
Front: 
**What are the steps involved in using Hartree SCF?**
Back: 
1. Make initial guess wavefunctions for each electron
2. Build $h_{i}$ operators for each wavefunction
3. Solve Schrödinger equation for each wavefunction
4. Use new set of wavefunctions to generate new set of $h_{i}$
5. Repeat until wavefunctions converge
Extra1:
![[Approximation Methods - Hartree SCF.png|500]]
Extra2:

Lesson: Approximation Methods
Course: CHEM4502
<!--ID: 1658631679995-->
END

START
Basic-lesson
Front: 
**What are the two major flaws of Hartree SCF for Approximation Methods?**
Back: 
- Electron-electron repulsion is double countered; can be corrected
- Does not account for spin, indistinguishability; can be corrected using Slater determinants ala Fock (to give Hartree-Fock theory) and create Fock operators ($f_{i}$)
Extra1:

Extra2:

Lesson: Approximation Methods
Course: CHEM4502
<!--ID: 1658631679999-->
END

START
Basic-lesson
Front: 
### Basics of Semiempricial Methods for Approximation Methods in Computational Chemistry?
Back: 
- Modify HF theory and simplify integrals
- Small, predefined basis sets, adjustable parameters used to estimate certain types of integrals
- Parameter values chosen to recreate certain experimental results

Extra1:
- Relatively fast, applicable to large systems
- Accuracy is suspect (order of magnitude calculations)
Extra2:

Lesson: Approximation Methods
Course: CHEM4502
<!--ID: 1658631680002-->
END

START
Basic-lesson
Front: 
### Basics of Perturbation Theory For Computational Chemistry?
Back: 
- Solutions are based on simple, solvable systems
- Simple systems are perturbed, resulting changes are determined
al)

Extra1:
- Works best when perturbations re small
- Does not provide upper limits to energy (i.e. is not variation
Extra2:
- Derivation summary
	- Write the Hamiltonian as a solvable function with an added perturbation $\hat H=\hat H^{(0)}+\hat H^{(1)}$
	- The wavefunction and energy can be written in simialr fashion 

$$\begin{align*}
&E=E^{(0)}+E^{(1)}+E^{(2)}+\dots\\
&\psi=\psi^{(0)}+\psi^{(1)}+\psi^{(2)}+\dots\end{align*}$$


We know or can find $\hat H^{(0)}, E^{(0)},\psi^{(0)}$
Lesson: Approximation Methods
Course: CHEM4502
<!--ID: 1658631680006-->
END

## Equations

START
Basic-lesson
Front: 
### Trial Wavefunction Equation



Back: 
$$\psi =\sum\limits_{i}c_{i}\phi_{i}$$
Extra1:
Use: Linear combination of simpler functions
Extra2:
- $\phi_{i}$=Basis set (Collection of basis functions)
- $c_{i}$= Scales functions
Lesson: Approximation Methods
Course: CHEM4502
<!--ID: 1658631680009-->
END

START
Basic-lesson
Front: 
### Variational Equation



Back: 
$$E_{0}\leq \frac{\int\psi_{i}\hat H \psi_{i}dr}{\int\psi_{0}^{2}dr}$$
Extra1:
Use: Approximated energies are always the upper limits to the real energy, and are calculated according the formula above:
Extra2:
Add definitions of variables later
Lesson: Approximation Methods
Course: CHEM4502
<!--ID: 1658631680012-->
END


START
Basic-lesson
Front: 
### The Secular Equation / Determinant


Back: 

$$\sum\limits_{i=1}^{N}c_{i}(H_{ij}-ES_{ij})=0$$


Extra1:
Use: Relates the coefficients of trial wavefunctions to their energies
Extra2:
- Determinant Format: 
$$
\begin{vmatrix}H_{11}-ES_{11}  & H_{12}-ES_{12} & \dots & H_{1N}-ES_{1N} \\ H_{21}-ES_{21} & H_{22}-ES_{22} & \dots \\ \vdots & \vdots & \ddots \\ H_{N1}-ES_{N1} &  &  & H_{NN}-ES_{NN}\end{vmatrix}=0
$$

Lesson: Approximation Methods
Course: CHEM4502
<!--ID: 1658631680017-->
END

START
Basic-lesson
Front: 
### Perturbational Energies Eqn
Back: 

$$E^{(1)}=\int \psi^{\star (0)} \hat H^{(1)} \psi^{(0)}$$


Extra1:
Use: Calculated from unperturbed wavefunction and is a correction to Hamiltonian
Extra2:
Variables later
Lesson: Approximation Methods
Course: CHEM4502
<!--ID: 1658631680020-->
END

START
Basic-lesson
Front: 
### Hartree Product Wavefunction Eqn



Back: 
$$\Psi_{HP}=\phi_{1}\phi_{2}\dots \phi_{N}$$
Extra1:
Use: The total wavefunction for a system is the product of the individual wavefunctions within it.
Extra2:

Lesson: Approximation Methods
Course: CHEM4502
<!--ID: 1658631680024-->
END

START
Basic-lesson
Front: 
### Hamiltonian of Entire System Using Hartree-Fock Methods Formulas


Back: 


$$\hat H=\sum\limits_{i=1}^{N}h_{i}$$
$$h_{i}=-\frac{1}{2}\nabla_{i}^{2}-\sum\limits_{k=1}^{M}\frac{Z_{k}}{r_{ik}}+V_{i}\{j\}$$
$$V_{i}\{j\}=\sum\limits_{i\neq j}\int\frac{\rho_{j}}{r_{ij}}dr$$

Extra1:
Use: The Hamiltonian of the entire system is the sum of one-electron Hamiltonian, which themselves describe an electron interacting with all nuclei and an average field from the other electrons
Extra2:
- $h_{i}$ is the one electron Hamiltonian
- $M$ is the total number of nuclei present
- $Z_{k}$ is the charge of the $k^{t h}$ nucleus
- $\rho_{j}$: electron density of electron j
Lesson: Approximation Methods
Course: CHEM4502
<!--ID: 1658631680028-->
END

START
Basic-lesson
Front: 
### Corrected Hartree SCF Formulas

Back: 

$$\hat H=\sum\limits_{i=1}^{N}f_{i}$$
$$f_{i}=-\frac{1}{2}\nabla_{i}^{2}-\sum\limits_{k=1}^{M}\frac{Z_{k}}{r_{ik}}+V_{i}\{j\}$$

Extra1:

Extra2:
Variables later
Lesson: Approximation Methods
Course: CHEM4502
<!--ID: 1658631680032-->
END

