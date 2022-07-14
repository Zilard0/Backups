---
tags: 🧠️/📝️/👨‍🏫/📥️
publish: true
aliases: 
---
# Chapter 5
Created: ### [[2022-06-28]]

### Classical Single body HO
* Figure
![[Pasted image 20220628034920.png|500]]

* Derivation:
$$\begin{align*}
&\text{Hooke's Law}\to F=-k \Delta x=-kx\\
&\text{Newton 2nd Law} \to F=ma\\
&\to m \frac{d^{2}x}{dt}+kx=0\\
&\to x(t)=c_{1}\sin(wt)+c_{2}\cos(wt)
\end{align*}$$
$$x(t)=A\cos(wt)$$
### Classical Two Body Harmonic Oscillator
* Figure:
![[Pasted image 20220628035727.png | 500]]




### Quantum Harmonic Oscillator
* Quantum harmonic oscillator: Two objects connected by a spring
* system satisfies a wave function
* Solutions are oscillatory and depend on a reduced mass ($\mu$) and force constant ($k$) 
* Solutions have several distinct parts: The hermite polynomials (Even/odd functions) are especially useful
* The QHO has a zero-point energy
* The QHO can tunnel into the potential barrier; a QHO can have a length greater than the initial amplitude.
* Requires KE < 0 (?)
* Hermite Polynomials: Even functions if v is even, odd if v is odd; useful property for integrals
	* $\left<x\right>=0$
	* $\left<p\right>=0$


### Quantum Rigid Rotor
* Figure:
![[Pasted image 20220628060104.png |500]]
* Derivation:
$$\begin{align*}
&u_{A}=2\pi r_{A}u=r_{A}\omega\\
&u_{B}=2\pi r_{B}u=r_{B}\omega\\
&KE_{tot}=\frac{1}{2}m_{A}u^{2}_{A}+\frac{1}{2}m_{B}u^{2}_{B}\\
&KE_{tot}=\frac{1}{2}m_{A}(r_{A}\omega)^{2}+\frac{1}{2}m_{B}(r_{A}\omega)^{2}\\
& =\frac{1}{2} I\omega^{2}\\
&\text{Where Angular momentum is }I\omega 
\end{align*}$$

* Quantum Rigid Rotor: Two objects connected at a fixed distance and rotating about a point in space
* System satisfies a wave function which is best expressed in spherical coordinates, that are called the spherical harmonics(Which require transforming the Hamiltonian)
* Angular momentum is an important Rigid Rotor Quantity
* Solutions depend on the moment of inertia ($I$) 
* There is no zero-point energy for the Rigid Rotor
* Quantized energies 
* Energy levels with degeneracies that are dependent on the quantum level
* Vibrational amplitudes are small (Typically $\leq 5$% of $R_{e}$ ), which makes the RR approximation reasonably valid

### Chapter 5 Equations

#### Wavenumber Eqn.
Use: In spectroscopy, we often use wavenumbers instead of frequency
$$\tilde v=\frac{v}{c} \to \text{unit is }cm^{-1} $$

#### 3-D volume element in spherical coordinates Integration

$$dxdydz=(r^{2}dr)(\sin\theta d \theta)(d\phi) \to\underbrace{\int_{0}^{2\pi}}_\phi\underbrace{\int_{0}^{\pi}}_\theta\underbrace{\int_{0}^{r}}_{r} r^{2}dr\sin(\theta)d\theta d\phi$$
* A point in a spherical coordinate system is specifed by the coordinates $r, \theta, \phi$ 

#### Reduced mass Eqn
Use: Effective mass at the center of mass of a multi body object.
$$\mu =\frac{m_{1}m_{2} }{m_{1}+m_{2}}$$

#### Quantum Harmonic Oscillator Eqns

##### Wavefunction of Quantum Harmonic Oscillator Eqn
$$\psi_{v}(x)=N_{v}H_{v}(x)\alpha^{\frac{1}{2}}e^{-\frac{\alpha x^{2}}{2}}$$

##### Reduced mass, force constant and Parameters of QHO
$$\alpha=\frac{\sqrt{k\mu}}{\hbar}$$
##### Energy Equations of QHO (Quantized)
$$E_{v}=hv\left(v+\frac{1}{2}\right)$$
* **NOTE THAT THERE ARE TWO DIFFERENT $v$ VALUES. THE ONE INSIDE THE BRACKETS IS AN INTEGER AND THE OTHER $v$ IS THE FREQUENCY**

##### Angular Frequency
$$\omega =\left(\frac{k}{\mu}\right)^{\frac{1}{2}} $$
add the other eqn later



#### Quantum Rigid Rotor Eqns

##### Moment of Inertia
$$I=\mu R^{2}$$
##### Energy of QRR (Quantized)
$$E_{l}=\frac{\hbar^{2}}{2I}l(l+1)$$
* Note that the book uses $J$ not $I$


##### Degeneracies of Energy Levels
$$g_{l}=2l+1$$

### Examples
**5-4&5-5: Show that $\psi_{0}(x)$ and $\psi_{1}(x)$ are normalized and are orthogonal for QHO**
$$\text{To show that they are normalized }\to \int_{-\infty}^{\infty}\psi^{*}_{o}\psi_{o}  dx= \int_{-\infty}^{\infty}\left[\left(\frac{\alpha}{\pi} \right)^{\frac{1}{4}}e^{-\frac{\alpha x^{2}}{2}} \right]^{2}d\alpha$$
$$=\left(\frac{\alpha}{\pi} \right)^{\frac{1}{2}}\int_{-\infty}^{\infty}\left[e^{-\frac{\alpha x^{2}}{2}} \right]=$$

Complete later and add notes about Gaussian integral

