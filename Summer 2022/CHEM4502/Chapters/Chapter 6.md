	---
tags: 🧠️/📝️/👨‍🏫/📥️
publish: true
aliases: 
---
# Chapter 6
Created:  [[2022-07-05]]

## Concepts
* Orbital: a unique set of $n,l,m$
* Subshell: a unique set of $n \text{ and } l$
* Shell: a unique set of $n$
* Total Angular Momentum is quantized
* Magnitude of Angular Momentum is determined by quantum number $l$
* Angular Momentum has units of $\hbar$ 
* Z-component of angular momentum is quantized
* Both total angular momentum and its z component can be known; their operators must commute
* There are $2l+1$ values of $m$ for any $l$ 
___

### Hydrogen Atom Solution
1. Angular (or $\theta \text{ and } \phi$ dependent) portion:
	* Gives rise to the spherical harmonics (the RR solutions in Ch 5) and the two quatum numbers ($l,m$) 
	* $l$ describes the length of the electron's angular momentum vector, or the total angular momentum
	* $m$ describes the z-axis projection of the angular momentum vector.
	* The x- and y- axis projections of the angular momentum vector are unknowable
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
* Can be expressed as a standard wave equation
* Can be solved exactly
* Adjusting Wavefunction formula for any one electron atom: $\sigma=\frac{Zr}{a_{o}}$
* Note that each $l$ value corresponds to a specific orbital type:
	* 0 = s
	* 1 = p
	* 2 = d
	* 3 = f
	* 4 = g

### Sketching Orbitals
* Spheres of no electron density
* Radii at which P(r) = 0 are called nodes
* Total number of nodes = $n-1$
* Number of angular nodes (Planes with no electron density) = $l$
* Number of radial nodes = $n-l-1$
* Number of orbitals in subshell = $2l+1$
* Linear combination of complex functions used to create real functions
* One can plot $R(r) \text{ or } [rR(r)]^{2}$ 
![[Pasted image 20220705084308.png|500]]
* Electron does not exist at fixed distance but has a probability of being found in some volume element
* Only m=0 functions

### Chapter 6 Eqns
#### Hamiltonian for Hydrogen Atom
$$\hat H_{H}=-\frac{\hbar^{2}}{2m_{e}}\nabla^{2}-\frac{e^{2}}{4\pi\epsilon_{o}r}$$
#### Basic Wavelength of Hydrogen Atom (Eigenfunction of Hamiltonian)
$$\psi(r,\theta,\phi)=R_{nl}(r)Y_{l}^{m}(\theta,\phi)$$


#### QM Energy of Hydrogen Atom in Fundamental Constants
$$E_{n}=-\frac{m_{e}e^{4}}{8\epsilon_{0}^{2}h^{2}n^{2}}=-\frac{e^{2}}{8\pi \epsilon_{o}a_{0}n^{2}}$$

#### Angular Momentum Vector Length of H Atom
$$|L|=[l(l+1)]^{\frac{1}{2}} \hbar$$

#### Z-axis Projection of Angular Momentum in H atom
$$|L_{Z}|=m\hbar$$

#### Soherical Harmonics Normalization Constant:
$$N_{lm}=\left[\frac{\left(2l+1\right)}{2}\frac{(l-|m|)!}{(l+|m|)!}\right]^\frac{1}{2}$$
### Examples

**6.1: Determine the value of $A_m$ so that the functions given by the Eqn 6.20 (wavefunction portion) are normalized**
$$\Phi=A_{m}e^{im\phi}$$
$$\int_{0}^{2\pi}\Phi^{*}\Phi d\phi=1=\int_{0}^{2\pi}[A_{m}e^{-im\phi}][A_{m}e^{im\phi}]d\phi=A_{m}^{2}\int_{0}^{2\pi}1d\phi$$
$$=A^{2}_{m }(2\pi)=1\to A_{m}=\sqrt{\frac{1}{2\pi}}$$
**6.5: Show that the hydrogenlike atomic wave function $\psi_{210}$ in Table 6.5 is normalized that it is orthogonal to $\psi_{200}$** 

$$\int\psi^{*}_{210}\psi_{210}=1$$

### In-Class Problems

6-1) Draw the angular momentum vector diagram of an electron in the a)3d, b)4f, and c)3s orbitals of hydrogen.


