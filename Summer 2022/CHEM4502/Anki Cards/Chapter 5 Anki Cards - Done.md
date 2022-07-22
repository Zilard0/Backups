START
Basic-lesson
Front: 
### Classical Single body HO


Back: 
* Figure
![[Pasted image 20220628034920.png|500]]

Extra1:
* Derivation:
$$\begin{align*}
&\text{Hooke's Law}\to F=-k \Delta x=-kx\\
&\text{Newton 2nd Law} \to F=ma\\
&\to m \frac{d^{2}x}{dt}+kx=0\\
&\to x(t)=c_{1}\sin(wt)+c_{2}\cos(wt)
\end{align*}$$
$$x(t)=A\cos(wt)$$
Extra2:

Lesson:
Course:
<!--ID: 1658513210636-->
END

START
Basic-lesson
Front: 
### Classical Two Body Harmonic Oscillator


Back: 
* Figure:
![[Pasted image 20220628035727.png | 500]]

Extra1:

Extra2:

Lesson:
Course:
<!--ID: 1658513210640-->
END

START
Basic-lesson
Front: 
### Quantum Harmonic Oscillator System



Back: 
* Quantum harmonic oscillator: Two objects connected by a spring
* system satisfies a wave function
* Solutions are oscillatory and depend on a reduced mass ($\mu$) and force constant ($k$) 
* Solutions have several distinct parts: The hermite polynomials (Even/odd functions) are especially useful
Extra1:
* The QHO has a zero-point energy
* The QHO can tunnel into the potential barrier; a QHO can have a length greater than the initial amplitude.
* Requires KE < 0 (?)
Extra2:

Lesson:
Course:
<!--ID: 1658513210643-->
END

START
Basic-lesson
Front: 
* Hermite Polynomials: 

Back: 
Even functions if v is even, odd if v is odd; useful property for integrals
Extra1:
	* $\left<x\right>=0$
	* $\left<p\right>=0$
Extra2:

Lesson:
Course:
<!--ID: 1658513210646-->
END

START
Basic-lesson
Front: 
### Quantum Rigid Rotor

Back: 
Quantum Rigid Rotor: Two objects connected at a fixed distance and rotating about a point in space
* Figure:
![[Pasted image 20220628060104.png |500]]

Extra1:

* System satisfies a wave function which is best expressed in spherical coordinates, that are called the spherical harmonics(Which require transforming the Hamiltonian)
* Angular momentum is an important Rigid Rotor Quantity
* Solutions depend on the moment of inertia ($I$) 
* There is no zero-point energy for the Rigid Rotor
* Quantized energies 
* Energy levels with degeneracies that are dependent on the quantum level
* Vibrational amplitudes are small (Typically $\leq 5$% of $R_{e}$ ), which makes the RR approximation reasonably valid

Extra2:
* Derivation:
$$\begin{align*}
&u_{A}=2\pi r_{A}u=r_{A}\omega\\
&u_{B}=2\pi r_{B}u=r_{B}\omega\\
&KE_{tot}=\frac{1}{2}m_{A}u^{2}_{A}+\frac{1}{2}m_{B}u^{2}_{B}\\
&KE_{tot}=\frac{1}{2}m_{A}(r_{A}\omega)^{2}+\frac{1}{2}m_{B}(r_{A}\omega)^{2}\\
& =\frac{1}{2} I\omega^{2}\\
&\text{Where Angular momentum is }I\omega 
\end{align*}$$

Lesson:
Course:
<!--ID: 1658513210650-->
END

START
Basic-lesson
Front: 
#### Wavenumber Eqn.
Back: 


$$\tilde v=\frac{v}{c} \to \text{unit is }cm^{-1} $$

Extra1:
Use: In spectroscopy, we often use wavenumbers instead of frequency
Extra2:

Lesson:
Course:
<!--ID: 1658513210654-->
END

START
Basic-lesson
Front: 
#### 3-D volume element in spherical coordinates Integration Formula

Back: 

$$dxdydz=(r^{2}dr)(\sin\theta d \theta)(d\phi) \to\underbrace{\int_{0}^{2\pi}}_\phi\underbrace{\int_{0}^{\pi}}_\theta\underbrace{\int_{0}^{r}}_{r} r^{2}dr\sin(\theta)d\theta d\phi$$

Extra1:
* A point in a spherical coordinate system is specifed by the coordinates $r, \theta, \phi$ 

Extra2:

Lesson:
Course:
<!--ID: 1658513210657-->
END

START
Basic-lesson
Front: 
#### Reduced mass Eqn

Back: 

$$\mu =\frac{m_{1}m_{2} }{m_{1}+m_{2}}$$


Extra1:
Use: Effective mass at the center of mass of a multi body object.
Extra2:

Lesson:
Course:
<!--ID: 1658513210661-->
END

START
Basic-lesson
Front: 
##### Wavefunction of Quantum Harmonic Oscillator Eqn
Back: 

$$\psi_{v}(x)=N_{v}H_{v}(x)\alpha^{\frac{1}{2}}e^{-\frac{\alpha x^{2}}{2}}$$

Extra1:

Extra2:

Lesson:
Course:
<!--ID: 1658513210664-->
END

START
Basic-lesson
Front: 
##### Reduced mass, force constant and Parameters of QHO Eqn

Back: 
$$\alpha=\frac{\sqrt{k\mu}}{\hbar}$$
Extra1:

Extra2:

Lesson:
Course:
<!--ID: 1658513210667-->
END

START
Basic-lesson
Front: 
##### Energy Equations of QHO (Quantized)



Back: 
$$E_{v}=hv\left(v+\frac{1}{2}\right)$$

Extra1:
* **NOTE THAT THERE ARE TWO DIFFERENT $v$ VALUES. THE ONE INSIDE THE BRACKETS IS AN INTEGER AND THE OTHER $v$ IS THE FREQUENCY**
Extra2:

Lesson:
Course:
<!--ID: 1658513210671-->
END

START
Basic-lesson
Front: 
##### Angular Frequency Eqn
Back: 

$$\omega =\left(\frac{k}{\mu}\right)^{\frac{1}{2}} $$
add the other eqn later
Extra1:

Extra2:

Lesson:
Course:
<!--ID: 1658513210674-->
END


START
Basic-lesson
Front: 

##### Moment of Inertia Eqn for QRR
Back: 

$$I=\mu R^{2}$$

Extra1:

Extra2:

Lesson:
Course:
<!--ID: 1658513210678-->
END

START
Basic-lesson
Front: 
##### Energy of QRR (Quantized)



Back: 
$$E_{l}=\frac{\hbar^{2}}{2I}l(l+1)$$
Extra1:
* Note that the book uses $J$ not $I$
Extra2:

Lesson:
Course:
<!--ID: 1658513210681-->
END

START
Basic-lesson
Front: 
##### Degeneracies of Energy Levels (QRR)


Back: 
$$g_{l}=2l+1$$
Extra1:

Extra2:

Lesson:
Course:
<!--ID: 1658513210684-->
END

