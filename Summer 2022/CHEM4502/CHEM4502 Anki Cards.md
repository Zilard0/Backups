Classical physics {{c1::fails}} to adequately describe emission spectra.

{{c1::Blackbody}}: absorbs all incident energy and reemits it as light
{{c1::Emitted spectrum}}: "Blackbody spectrum" Unique for any temperature


Electrons are ejected from a metal surface when light is shone on it. The approach of classical physics was that all frequencies of light should cause electron emission if intensity is sufficient. However, this is wrong; there is a {{c1::threshold frequency $v_{o}$}} for electron emission, regardless of intensity


* Bare atoms absorb specific frequencies of light
* When excited, atoms emit the exact same frequencies as they relax
* Classical physics couldn't explain the existence/energies of these spectral lines

#### Kinetic Energy of Photoelectron
$$eKE=hv- \phi =\frac{1}{2}mu^{2}$$
* $v$ = frequency of photon used to detach it
* $\phi$ = amount of energy need to remove it from its parent atom
* $m$ = mass of object
* $u$ = velocity of object

#### Rydberg Equation
Use: Describes the spectrum of atomic hydrogen
$$E= \frac{1}{\lambda}=Z^{2}R_{H}[\frac{1}{n^{2}_{i}}-\frac{1}{n^{2}_{f}}]$$
* $Z$ = nuclear charge
* $R_H$ = Proportionality constant
* $n_i$ = initial energy level of atom/ion
* $n_f$ = initial energy level of atom/ion
	* Note that hte energy of a wave can be expressed as the inverse of the wavelength, which gives them the units of $m^{-1}$ or $cm^{-1}$ , called wavenumber.
	* $E < 0 \textrm{ for emission}$ 
	* $E > 0 \textrm{ for absorption}$ 

#### Energy of Light
Use: Relates the energy of a light particle, or a photon to its frequency
$$E=hv$$
#### Bohr's Eqn for the radius and energy of an Electron for Hydrogen
$$r=\frac{4\pi\epsilon_{o}\hbar^{2}n^{2}}{m_{e}e^{2}} \qquad \qquad E=-\frac{m_{e}e^{4}}{8\epsilon^{2}_{o}h^{2}n^{2}}$$

* $\hbar$ = $\frac{h}{2\pi}$ 
* $n=1$ is the ground state (Lowest possible E)
* $n > 1$ is an excited state

#### Bohr's derived value of Rydberg Constant
$$R_{H}\approx \frac{m_{e}e^{4}}{8\epsilon^{2}_{o}h^{3}c}$$
* $c$ = speed of light

#### de Broglie Relationship
$$\lambda =\frac{h}{mu}$$
* **Note that $\lambda$ here refers to the wavelength of a particle**

#### Uncertainty of a particle's position and momentum.
$$\Delta x\Delta p \geq \frac{\hbar}{2}$$
* Note that this has the smallest value compared to other similar equations
* These uncertainties has a minimum allowed value.


#### Quantum Mechanics:
* Treats electrons as waves
* based on the classical wave equation
* Boundaries: Restrict the infinite possible solution of a wave to the edges of interest.


### Chapter 2 Equations
#### Speed of Wave

$$c=v\lambda$$
* Not that it is not interchangeable with de Broglie Eqn!!

#### Wave's Frequency & Angular Frequency
$$v=\frac{\omega}{2\pi}$$
* $\omega$ = Angular Frequency

#### Classical Wave Equation
$$\frac{\partial^{2} f(x,t)}{\partial x^{2}}=\frac{\partial^{2} f(x,t)}{u^2\partial t^{2}}$$
* $u$ = speed of wave
* The solutions to the wave eqauation are either imaignary, zero, or sums of sines and cosines.
* Add picture here from video later
* 
#### Solutions to Classical Wave Equation

$$X(x)=c_{1}e^{i\beta x}+ c_{2}e^{i\beta x} = c_{3}cos{\beta x}+c_{4}sin{\beta x}$$
#### Solution to Temporal Portion of wave Equation
$$T(t)=c_{5}cos{\frac{un\pi t}{l}}+c_{6}sin{\frac{un\pi t}{l}}$$
* $n$ = integer
* $l$ = length of space

#### Total Wave Function Eqn
$$f_{n}(x,t) =X_n(x)T_{n(t)}\qquad \qquad f(x,t) =\sum_{n=1}^{\infty} f_{n}(x,t)$$

**Orthogonality**: The cross product of linearly independent vectors is zero.
* **Orthonormal** **vectors**: Vectors that are both normalized and orthogonal. Sets of wavefunctions are orthonormal.
* **Commutators**: A mathematical check whether the order of operations matter. Also, operators commute if their eigenvalues can simultaneously be measured.
* The eigenfunctions, or wavefunctions, allow for predictions to be made about physical observables according to postulates.
* **Correspondence Principle**: Quantum Mechanics results must match macroscopic observations when applied to macro systems.
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
Use: AN operator, its eigenfunctions, and the eigenvalues are defined by a specific relationship.
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


**Distribution**: a set of possible values $x$ and their associated proabilites of occuring $y$ 
* **Normality**: The sum of all probabilities is 1 or 100%
* **Mean**: Average outcome of an experiment based on the distribution

## Math Chapter B Eqns
#### Variance
$$\sigma^{2}= \langle x^{2}\rangle-\langle x \rangle^{2} \geq 0$$
### Discrete Distribution Eqns
#### Probability that the system exists between first and nth state
$$P=\sum_{i=1}^{n}p_i$$
#### Probability if range includes all possibilities
$$1=\sum_{i=1}^{n}p_i$$
#### Mean value over range 1 to n of a quantity associated with the operator $\hat A_{i}$ 
$$\langle \hat A \rangle=\sum_{i=1}^{n}\hat A_{i}p_{i}$$


### Continuous Distribution Eqns
#### Probability that the system exists between a and b states
$$P=\int_{a}^{b}p(x)dx$$
#### Probability if range includes all possibilities (Normalized)
$$1=\int_{\text{all space}} Ap (x)dx$$
