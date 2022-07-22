---
tags: 🧠️/📝️/👨‍🏫/📥️
publish: true
aliases: 
---
# Chapters 3/4
Created: ### [[2022-07-14]]
___
## Concepts
**Orthogonality**: The cross product of linearly independent vectors is zero.
* **Orthonormal** **vectors**: Vectors that are both normalized and orthogonal. Sets of wavefunctions are orthonormal.
* **Commutators**: A mathematical check whether the order of operations matter. Also, operators commute if their eigenvalues can simultaneously be measured.
* The eigenfunctions, or wavefunctions, allow for predictions to be made about physical observables according to postulates.
* **Correspondence Principle**: Quantum Mechanics results must match macroscopic observations when applied to micro systems.
* **Tunneling**: Existence of Quantum Mechanics' particles in classically forbidden regions
* **Observable**: Something measurable
* **Operator**: Performs a mathematical operation on a function
* Linear Operator (Hamilitan) = $\hat A(f+g)= \hat A f+ \hat A g$

## Notes
### Postulates

#### Postulate 1
Statement: There is a wavefunction $(\psi(\boldsymbol{x}))$  for any Quantum Mechanics system.
Conditions:
* The wavefunction is a solution to a wave equation
* The wavefunction must be well-behaved (Normalized) over its allowed interval (Particle must be **somewhere** in the allowed space)
	* $\psi(\boldsymbol x),\psi^{'}(\boldsymbol x)$ must be single-valued
	* $\psi(\boldsymbol x),\psi^{'}(\boldsymbol x)$ must be continuous
	* $\psi(\boldsymbol x),\psi^{'}(\boldsymbol x)$ must be finite
	* $\psi(\boldsymbol x)$ must approach 0 as $\boldsymbol x \to \pm \infty$ 
* The probability the particle for a quantum mechanics system lies between $x$ and $x+dx$ is related to $\psi^{*}(\boldsymbol{x})\psi(\boldsymbol{x})dx$
* Can be extended to multi-particle systems.

#### Postulate 2
Statement: There are operators for all physical observables
Operator: A function which operates on a function

#### Postulate 3
Statement: The operators have eigenvalues, and physical observables take values which are eigenvalues of their operators.
Condition:
* The eigenvalue $a$ of an eigenfunction $(\psi(x))$ for an operator $\hat A$ obeys: $\hat A \psi(x)=a\psi(x)$ 
* Wavefunctions may be imaginary/complex; Observables must be real.
* QM operators must be Hermitian, because eigenvalues of Hermitian operators must be real.


#### Postulate 4
Statement: The average (or expected) value of an operator's eigenvalue can be determined if the normalized wavefunction is known.
Condition:
* The operator must be inserted into the distribution function in the proper location: $$\langle a \rangle =\int_{\textrm{all space}} \psi^{*}\hat A \psi\ dx=a\int_{\textrm{all space}} \psi^{*} \psi\ dx=a(1)=a$$

#### Postulate 5
Statement: Wavefunctions may evolve over time. However, in this course we are interested only in stationary states (do not change over time).

### Particle in a 1-D Box
Eqn: 

![[2022-06-17 05-53-57.excalidraw]]

Conditions:
* $\psi(0)=\psi(a)=0$

#### Derivation

$$\hat H\psi=\left[-\frac{\hbar^{2}}{2m}\frac{d^{2}}{dx^{2}}+0\right]\psi- E\psi= -\frac{\hbar^{2}}{2m}\frac{d^{2}}{dx^{2}}\psi- E\psi$$
$$\textrm{Solution from Chapter 2: } \psi (0)=0=A\cos0+B\sin0 =A(1)+0=A$$
$$\psi (a)=0=B\sin ka \qquad \textrm{If } ka=n \pi \to k=n \pi =\frac{n \pi }{a}$$
$$\psi (x)=B\sin \frac{n \pi}{a}x \qquad n=1,2,3,\dots$$
$$\hat H\psi=E\psi , \textrm{where }E=\frac{h^{2}n^{2}}{8ma^{2}} \textrm{ is quantized.}$$
#### Normalization
$$1=\int_{\textrm{all space}} \psi^{*}\psi=B^{2}\int_{\textrm{all space}} \sin \frac{n \pi x}{a}\sin \frac{n \pi x}{a}dx =B^{2}\left(\frac{a}{2}\right) \to B=\sqrt{\frac{2}{a}} $$
$$\psi(x)= \sqrt{\frac{2}{a}} \sin \frac{n \pi x}{a}$$

#### Solutions' Figure
![[Pasted image 20220617190134.png]]
* $Nodes=n-1$ 
* $P=\psi^{*}\psi=\psi^{2}$ 

### 2-D Particle in Box
#### Figure:
![[2022-06-17 19-20-18.excalidraw]]
#### Equation:
$$\psi(x)= \sqrt{\frac{4}{ab}} \sin \frac{n_{x} \pi x}{a}\sin \frac{n_{y} \pi y}{a}$$
### Chapters 3/4 Equations

#### Postulate 1 Equation
Use: Provides a valid statistical distribution from the wavefunction
$$p(\boldsymbol x)dx=\psi^{*}(\boldsymbol{x})\psi(\boldsymbol{x})d\boldsymbol x$$
* $\psi^{*}$ = Complex conjugate of $\psi$ (Replace the sign of the $i$ part in the function. That's it)
#### Operator Effect on Functions
Use: An operator acts on a function to give a new function
$$\hat A f(x)=g(x)$$

#### Postulate 2's Equation
Use: An operator, its eigenfunctions, and the eigenvalues are defined by a specific relationship.
$$\hat A f(x)=af(x)$$
* $a$=Eigenvalue
* $f(x)$ = Eigenfunction of $\hat A$

#### Postulate 5's Equation
Use: Explains how wavefunctions evolve over time.
$$\hat H\Psi(x,t)=i\hbar\frac{\partial \Psi(\boldsymbol x,t)}{\partial t} $$

#### Wavefunctions' Orthonormality
Use: Wavefunctions satisify orthonormality.
$$\int_{\textrm{all space}}\psi^{*}_{i}\psi_{j}d\vec{x}=\delta_{ij}\begin{cases}
=0,\ \ i\neq j \\
=1,\ \ i=j
\end{cases}$$
* $\delta_{ij}$ :  Kronecker delta function
* if $\int_\textrm{all space}\psi_{i}^{*}\psi_{j}=0$ then $i\neq j$  
* if $\int_\textrm{all space}\psi_{i}^{*}\psi_{j}=1$ then $i=j =i$   

#### Operators' Commutation Eqn
Use: Two operators ($\hat A$ and $\hat B$) commute if their commutator equals zero.
$$[\hat A, \hat B ]f=\hat B \hat Af-\hat A\hat B f$$


#### Time-Independent Schrodinger Eqn
Use: The time-independent Schrodinger equation is the basic starting point for determining wavefunctions. We solve for eigenvalues and eigenfunctions of QM operators. Also, the potential energy operator defines a particular QM.
$$\hat H\psi=\left[-\frac{\hbar^{2}}{2m}\frac{d^{2}}{dx^{2}}+V(x)\right]\psi=E\psi$$
* $\hat H$ = Hamiltonian

#### Wavefunction of Particle in 1-D Box
$$\psi(x)= \sqrt{\frac{2}{a}} \sin \frac{n \pi x}{a}$$
#### Wavefunction of Particle in 2-D Box
$$\psi(x)= \sqrt{\frac{4}{ab}} \sin \frac{n_{x} \pi x}{a}\sin \frac{n_{y} \pi y}{a}$$

#### Wavefunction of Particle in 3-D Box
$$\psi(x)= \sqrt{\frac{8}{abc}} \sin \frac{n_{x} \pi x}{a}\sin \frac{n_{y} \pi y}{a}\sin \frac{n_{y} \pi z}{c}$$

#### Energies' Eqns of Particles in Boxes:
1-D Box:
$$E=\frac{h^{2}}{8m}\left(\frac{n^{2}}{a^{2}}\right)$$

2-D Box:
$$E=\frac{h^{2}}{8m}\left(\frac{n_{x}^{2}}{a^{2}}+\frac{n_{y}^{2}}{b^{2}}\right)$$

3-D Box:

$$E=\frac{h^{2}}{8m}\left(\frac{n_{x}^{2}}{a^{2}}+\frac{n_{y}^{2}}{b^{2}}+\frac{n_{z}^{2}}{c^{2}}\right)$$

#### Wavefunction of Particle in 3-D Box
$$\psi(x)= \sqrt{\frac{8}{abc}} \sin \frac{n_{x} \pi x}{a}\sin \frac{n_{y} \pi y}{a}\sin \frac{n_{y} \pi z}{c}$$

#### Common Operators' Eqns
![[Pasted image 20220617030455.png]]