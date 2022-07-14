# Quiz 2 Summary
## Definitions
* Orbital: a unique set of $n,l,m$
* Subshell: a unique set of $n \text{ and } l$
* Shell: a unique set of $n$


## Concepts

### Angular Momentum
* Total Angular Momentum is quantized
* $l$ describes the length of the electron's angular momentum vector (magnitude), or the total angular momentum
* Angular Momentum has units of $\hbar$ 
* $m$ describes the z-axis projection of the angular momentum vector.
* Z-component of angular momentum is quantized
* The x- and y- axis projections of the angular momentum vector are unknowable
* Both total angular momentum and its z component can be known; their operators must commute
* There are $2l+1$ values of $m$ for any $l$ 
* Note that each $l$ value corresponds to a specific orbital type:
	* 0 = s
	* 1 = p
	* 2 = d
	* 3 = f
	* 4 = g



### Hydrogen Atom Solution
* Angular (or $\theta \text{ and } \phi$ dependent) portion:
	* Gives rise to the spherical harmonics (the RR solutions in Ch 5) and the two quantum numbers ($l,m$) 
	* Solution to $\theta$ :
$$(1-x^{2})\left(\frac{d^{2}P}{dx^{2}}\right)-2x \frac{dP}{dx}+\left[l(l+1)-\frac{m^{2}}{1-x^{2}}\right]P(x)=0$$
* Solutions are called the Legendre polynomials, $P_{l}^{|m|}$
	* $l=0,1,2,\dots$
	* $m_{l}=0,\pm1,\pm2,\dots,\pm l$    
 

2. Radial (or $r$ dependent) portion:
	* polynomial and exponential functions of $r$
	* Gives quantum number $n$
	* Three quantum numbers:
		* $n =1,2,3,\dots$; determine energy
		* $l = 0,1,2,\dots,n-1$; determine shape
		* $m=0,\pm1,\pm2,\dots,\pm l$; determines the orientation 

* Fixed proton orbited by one electron:
$$\hat H_{H}=-\frac{\hbar^{2}}{2m_{e}}\nabla^{2}-\frac{e^{2}}{4\pi\epsilon_{o}r}$$
* Can be expressed as a standard wave equation, and can be solved exactly
* Adjusting Wavefunction formula for any one electron atom: $\sigma=\frac{Zr}{a_{o}}$

### Sketching Orbitals
* Orbitals are spheres of no electron density
* Number of orbitals in subshell = $2l+1$
* Radii at which P(r) = 0 are called nodes
	* Total number of nodes = $n-1$
	* Number of angular nodes (Planes with no electron density) = $l$
	* Number of radial nodes = $n-l-1$

* Linear combination of complex functions used to create real functions
* One can plot $R(r) \text{ or } [rR(r)]^{2}$ 
![[Pasted image 20220705084308.png|500]]
* Electron does not exist at fixed distance but has a probability of being found in some volume element
* Only m=0 functions (I have no clue why is this a condition but gonna ask later I guess)


### Spin
* Electrons have an inherent, fundamental angular momentum which we call "spin"
* The length and z-axis projection of the spin vector are quantized; the z-axis projection gives a fourth quantum number; $m_{s}$ (Note that $m_{l}$ is used for z component of orbital angular momentum)
* Spin add another contribution to the H atom wavefunction
* Spin is necessary for describing multielectron systems
* There must be operators and eigenfunctions for spin
* We do not know their forms, only the associated eigenvalues
* Spin has no classical analog (which means it does not make sense to interpret it using classical physics); it is purely QM Effect
* Notation for spin wavefunctions:![[2022-07-07 07-43-53.excalidraw|75]]

### Antisymmetry
* Electrons in a system cannot be distinguished (Indistinguishability); we must consider all possible arrangements
* Antisymmetry Formula:

$$\begin{align*}

&\Psi_{He}(1,2)=(\psi_{1s}\alpha)_{1}(\psi_{1s}\beta)_{2}\\
&\Psi_{He}(2,1)=(\psi_{1s}\alpha)_{2}(\psi_{1s}\beta)_{1}\\
\end{align*}\qquad \text{They are the same}!$$
* Antisymmetry Options:
	* Option 1: $\Psi_{1}=\Psi(1,2)+\Psi(2,1)=\frac{1}{\sqrt{2}}(\psi_{1s}\alpha)_{1}(\psi_{1s}\beta)_{2}+\frac{1}{\sqrt{2}}(\psi_{1s}\alpha)_{2}(\psi_{1s}\beta)_{1}$
	* Option 2: $\Psi_{2}=\Psi(1,2)-\Psi(2,1)=\frac{1}{\sqrt{2}}(\psi_{1s}\alpha)_{1}(\psi_{1s}\beta)_{2}-\frac{1}{\sqrt{2}}(\psi_{1s}\alpha)_{2}(\psi_{1s}\beta)_{1}$
* Antisymmetry is if $\Psi_{1}=-\Psi_{2}$

### Postulate 6:
Statement: All electron wavefunctions must be antisymmetric with respect to exchange of any two electrons
* Antisymmetric wavefunctions are most easily expressed with determinants
$$\Psi=\frac{1}{\sqrt{2}}\begin{vmatrix}(\psi_{1s}\alpha)_{1} & (\psi_{1s}\beta)_{1} \\ (\psi_{1s}\alpha)_{2} & (\psi_{1s}\beta)_{2}\end{vmatrix}$$

* Pauli Exculsion Principle: No two electrons in an atom can have the same set of four quantum numbers


### Term symbols:
* Shorthand method of describing the entire wavefunction of a multielectron atom
* Term symbols and selection rules help to elucidate atomic spectra
* Specify the values of $m_{l}$ and $m_{l}$ for all electrons in an atom at the same time
* Symbol:
$$^{2S+1}L_{J}$$
* $L$ is represented by a letter:
	* L = 0 is S
	* L = 1 is P
	* L = 2 is D
	* L = 3 is F
	* L = 4 is G

### Hund's Rules
* Used to determine ground state term symbols of atoms
* E increases as S decreases; High spin is preferred
* If S is the same, E increases as L decreases; High orbital angular momentum is preferred
* If S and L are the same:
	* Small J is preferred if subshell is < half full
	* Large J is preferred if subshell is > half full

### Atomic Spectra
* Atomic spectra arise from transitions between electron configurations (terms)
* Energies in atomic spectra generally depend on spin-orbit coupling; no truly degenerate states, even in H
* Selection rules for transitions:
	* $\Delta L=\pm 1$
	* $\Delta S=0$
	* $\Delta J=0, \pm 1$ except (J=0 to J=0)
* Lines in H spectra are actually doublets
* Small splitting in the spectra are called fine structure.

## Chapter 6 Equations
#### Hamiltonian for Hydrogen Atom
$$\hat H_{H}=-\frac{\hbar^{2}}{2m_{e}}\nabla^{2}-\frac{e^{2}}{4\pi\epsilon_{o}r}$$
#### Basic Wavefunction of Hydrogen Atom (Eigenfunction of Hamiltonian)
$$\psi(r,\theta,\phi)=R_{nl}(r)Y_{l}^{m}(\theta,\phi)$$


#### QM Energy of Hydrogen Atom in Fundamental Constants
$$E_{n}=-\frac{m_{e}e^{4}}{8\epsilon_{0}^{2}h^{2}n^{2}}=-\frac{e^{2}}{8\pi \epsilon_{o}a_{0}n^{2}}$$

#### Angular Momentum Vector Length of H Atom
$$|L|=[l(l+1)]^{\frac{1}{2}} \hbar$$

#### Z-axis Projection of Angular Momentum in H atom
$$|L_{Z}|=m\hbar$$

#### Soherical Harmonics Normalization Constant:
$$N_{lm}=\left[\frac{\left(2l+1\right)}{2}\frac{(l-|m|)!}{(l+|m|)!}\right]^\frac{1}{2}$$

## Chapter 8 Equations

#### Length of Spin Angular Momentum Vector
$$|S|=[s(s+1)]^{\frac{1}{2}}\hbar$$


#### Spin Multiplicity
$$2S+1$$
* $S$ = Total spin angular momentum
* Unpaired electrons = $2S$ 

#### Z-axis projection of the spin angular momentum vector
$$|S_{z}|=\pm \frac{1}{2}\hbar$$

#### The Determinental wavefunction
Use: Efficient way to write antisymmetric wavefunctions

$$\Psi = \frac{1}{\sqrt{N!}}
\begin{vmatrix}(\psi_{1})_{1} & (\psi_{2})_{1} & \dots & (\psi_{N})_{1} \\ (\psi_{1})_{2} & (\psi_{2})_{2} & \dots & (\psi_{N})_{2} \\ (\psi_{1})_{1} & (\psi_{2})_{1} & \ddots & \vdots  \\ (\psi_{1})_{N} & (\psi_{2})_{N} & \dots & (\psi_{N})_{N}\end{vmatrix}$$

#### Number of Microstates Available to Specific Electron Configuration

$$\text{Microstates = }\prod_\text{subshells} \frac{g_{k}!}{N_{k}!(g_{k}-N_{k})!} $$
* $g_{k}$ = Number of places an electron can fit in that subshell
* $N_{k}$ = Number of electrons in that subshell

#### Term Symbols Formulas 
##### Total Orbital Angular Momentum (L)
$$L=\sum\limits_{i}m_{l_{i}}$$
##### Total Spin Angular Momentum (S)
$$S=\sum\limits_{i}m_{s_{i}}$$

##### Russell-Saunders Coupling (J)
$$J=|L+S|,|L+S|-1,|L+S|-2,\dots,|L-S| $$
