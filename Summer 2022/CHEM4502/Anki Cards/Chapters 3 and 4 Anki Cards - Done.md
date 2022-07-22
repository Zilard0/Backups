START
Basic-lesson
Front: 
**Orthogonality**
Back: 
The cross product of linearly independent vectors is zero.
Extra1:
Extra2:
Lesson: Chapters 3&4 
Course: CHEM4502
<!--ID: 1658507444103-->
END

START
Basic-lesson
Front: 
**Orthonormal** **vectors**
Back: 
 Vectors that are both normalized and orthogonal. Sets of wavefunctions are orthonormal.
Extra1:
Extra2:

Lesson: Chapters 3&4
Course: CHEM4502
<!--ID: 1658507444111-->
END

START
Basic-lesson
Front: 
**Commutators**:
Back: 
A mathematical check whether the order of operations matter. Also, operators commute if their eigenvalues can simultaneously be measured.
Extra1:

Extra2:

Lesson: Chapters 3&4
Course: CHEM4502
<!--ID: 1658507444116-->
END


START
Basic-lesson
Front: 
The eigenfunctions, or wavefunctions, allow ......
Back: 
for predictions to be made about physical observables according to postulates.
Extra1:

Extra2:

Lesson: Chapters 3&4
Course: CHEM4502
<!--ID: 1658507444123-->
END

START
Basic-lesson
Front: 
**Correspondence Principle**
Back: 
Quantum Mechanics results must match macroscopic observations when applied to micro systems.
Extra1:

Extra2:

Lesson: Chapters 3&4
Course: CHEM4502
<!--ID: 1658507444130-->
END


START
Basic-lesson
Front: 
**Tunneling**
Back: 
Existence of Quantum Mechanics' particles in classically forbidden regions
Extra1:

Extra2:

Lesson: Chapters 3&4
Course: CHEM4502
<!--ID: 1658507444135-->
END

START
Basic-lesson
Front: 
**Observable**: 
Back: 
Something measurable
Extra1:

Extra2:

Lesson: Chapters 3&4
Course: CHEM4502
<!--ID: 1658507444141-->
END

START
Basic-lesson
Front: 
**Operator**: 
Back: 
Performs a mathematical operation on a function
Extra1:

Extra2:

Lesson: Chapters 3&4
Course: CHEM4502
<!--ID: 1658507444147-->
END

START
Basic-lesson
Front: 
Linear Operator (Hamilitan) = 
Back: 
$\hat A(f+g)= \hat A f+ \hat A g$
Extra1:

Extra2:

Lesson: Chapters 3&4
Course: CHEM4502
<!--ID: 1658507444152-->
END

START
Basic-lesson
Front: 
#### Postulate 1
Statement: 

Back: 
There is a wavefunction $(\psi(\boldsymbol{x}))$  for any Quantum Mechanics system.
Extra1:
Conditions:
* The wavefunction is a solution to a wave equation
* The wavefunction must be well-behaved (Normalized) over its allowed interval (Particle must be **somewhere** in the allowed space)
	* $\psi(\boldsymbol x),\psi^{'}(\boldsymbol x)$ must be single-valued
	* $\psi(\boldsymbol x),\psi^{'}(\boldsymbol x)$ must be continuous
	* $\psi(\boldsymbol x),\psi^{'}(\boldsymbol x)$ must be finite
	* $\psi(\boldsymbol x)$ must approach 0 as $\boldsymbol x \to \pm \infty$ 

Extra2:
* The probability the particle for a quantum mechanics system lies between $x$ and $x+dx$ is related to $\psi^{*}(\boldsymbol{x})\psi(\boldsymbol{x})dx$
* Can be extended to multi-particle systems.

Lesson: Chapters 3&4
Course: CHEM4502
<!--ID: 1658507444157-->
END

START
Basic-lesson
Front: 
#### Postulate 2
Statement: 

Back: 
There are operators for all physical observables
Extra1:

Extra2:

Lesson: Chapters 3&4
Course: CHEM4502
<!--ID: 1658507444163-->
END

START
Basic-lesson
Front: 
#### Postulate 3
Statement: 

Back: 
The operators have eigenvalues, and physical observables take values which are eigenvalues of their operators.
Extra1:
Condition:
* The eigenvalue $a$ of an eigenfunction $(\psi(x))$ for an operator $\hat A$ obeys: $\hat A \psi(x)=a\psi(x)$ 
* Wavefunctions may be imaginary/complex; Observables must be real.
* QM operators must be Hermitian, because eigenvalues of Hermitian operators must be real.

Extra2:

Lesson: Chapters 3&4
Course: CHEM4502
<!--ID: 1658507444168-->
END

START
Basic-lesson
Front: 
#### Postulate 4
Statement:

Back: 
 The average (or expected) value of an operator's eigenvalue can be determined if the normalized wavefunction is known.

Extra1:
Condition:
* The operator must be inserted into the distribution function in the proper location: $$\langle a \rangle =\int_{\textrm{all space}} \psi^{*}\hat A \psi\ dx=a\int_{\textrm{all space}} \psi^{*} \psi\ dx=a(1)=a$$
Extra2:

Lesson: Chapters 3&4
Course: CHEM4502
<!--ID: 1658507444174-->
END

START
Basic-lesson
Front: 
#### Postulate 5
Statement: 
Back: 
 Wavefunctions may evolve over time. However, in this course we are interested only in stationary states (do not change over time).
Extra1:

Extra2:

Lesson: Chapters 3&4
Course: CHEM4502
<!--ID: 1658507444180-->
END

START
Basic-lesson
Front: 
### Particle in a 1-D Box


Back: 
Figure: 

![[2022-06-17 05-53-57.excalidraw]]

Extra1:
Conditions:
* $\psi(0)=\psi(a)=0$

Extra2:
#### Derivation

$$\hat H\psi=\left[-\frac{\hbar^{2}}{2m}\frac{d^{2}}{dx^{2}}+0\right]\psi- E\psi= -\frac{\hbar^{2}}{2m}\frac{d^{2}}{dx^{2}}\psi- E\psi$$
$$\textrm{Solution from Chapter 2: } \psi (0)=0=A\cos0+B\sin0 =A(1)+0=A$$
$$\psi (a)=0=B\sin ka \qquad \textrm{If } ka=n \pi \to k=n \pi =\frac{n \pi }{a}$$
$$\psi (x)=B\sin \frac{n \pi}{a}x \qquad n=1,2,3,\dots$$
$$\hat H\psi=E\psi , \textrm{where }E=\frac{h^{2}n^{2}}{8ma^{2}} \textrm{ is quantized.}$$
#### Normalization
$$1=\int_{\textrm{all space}} \psi^{*}\psi=B^{2}\int_{\textrm{all space}} \sin \frac{n \pi x}{a}\sin \frac{n \pi x}{a}dx =B^{2}\left(\frac{a}{2}\right) \to B=\sqrt{\frac{2}{a}} $$
$$\psi(x)= \sqrt{\frac{2}{a}} \sin \frac{n \pi x}{a}$$

Lesson: Chapters 3&4
Course: CHEM4502
<!--ID: 1658507444185-->
END

START
Basic-lesson
Front: 
#### Solutions' to 1-D Box Figure


Back: 
![[Pasted image 20220617190134.png]]
Extra1:
* $Nodes=n-1$ 
* $P=\psi^{*}\psi=\psi^{2}$ 
Extra2:

Lesson: Chapters 3&4
Course: CHEM4502
<!--ID: 1658507444190-->
END

START
Basic-lesson
Front: 
### 2-D Particle in Box
#### Figure:

Back: 

![[2022-06-17 19-20-18.excalidraw]]

Extra1:
#### Equation:
$$\psi(x)= \sqrt{\frac{4}{ab}} \sin \frac{n_{x} \pi x}{a}\sin \frac{n_{y} \pi y}{a}$$

Extra2:

Lesson: Chapters 3&4
Course: CHEM4502
<!--ID: 1658507444196-->
END

START
Basic-lesson
Front: 
#### Postulate 1 Equation



Back: 
$$p(\boldsymbol x)dx=\psi^{*}(\boldsymbol{x})\psi(\boldsymbol{x})d\boldsymbol x$$
Extra1:
Use: Provides a valid statistical distribution from the wavefunction
Extra2:
* $\psi^{*}$ = Complex conjugate of $\psi$ (Replace the sign of the $i$ part in the function. That's it)
Lesson: Chapters 3&4
Course: CHEM4502
<!--ID: 1658507444201-->
END

START
Basic-lesson
Front: 
#### Operator Effect on Functions Eqn
Back: 


$$\hat A f(x)=g(x)$$

Extra1:
Use: An operator acts on a function to give a new function
Extra2:

Lesson: Chapters 3&4
Course: CHEM4502
<!--ID: 1658507444206-->
END

START
Basic-lesson
Front: 
#### Postulate 2's Equation
Back: 


$$\hat A f(x)=af(x)$$

Extra1:
Use: An operator, its eigenfunctions, and the eigenvalues are defined by a specific relationship.
Extra2:
* $a$=Eigenvalue
* $f(x)$ = Eigenfunction of $\hat A$
Lesson: Chapters 3&4
Course: CHEM4502
<!--ID: 1658507444211-->
END

START
Basic-lesson
Front: 
#### Postulate 5's Equation



Back: 
$$\hat H\Psi(x,t)=i\hbar\frac{\partial \Psi(\boldsymbol x,t)}{\partial t} $$
Extra1:
Use: Explains how wavefunctions evolve over time.
Extra2:

Lesson: Chapters 3&4
Course: CHEM4502
<!--ID: 1658507444216-->
END

START
Basic-lesson
Front: 
#### Wavefunctions' Orthonormality



Back: 
$$\int_{\textrm{all space}}\psi^{*}_{i}\psi_{j}d\vec{x}=\delta_{ij}\begin{cases}
=0,\ \ i\neq j \\
=1,\ \ i=j
\end{cases}$$
Extra1:
Use: Wavefunctions satisify orthonormality.
Extra2:
* $\delta_{ij}$ :  Kronecker delta function
* if $\int_\textrm{all space}\psi_{i}^{*}\psi_{j}=0$ then $i\neq j$  
* if $\int_\textrm{all space}\psi_{i}^{*}\psi_{j}=1$ then $i=j =i$   

Lesson: Chapters 3&4
Course: CHEM4502
<!--ID: 1658507444221-->
END

START
Basic-lesson
Front: 
#### Operators' Commutation Eqn

Back: 

$$[\hat A, \hat B ]f=\hat B \hat Af-\hat A\hat B f$$

Extra1:
Use: Two operators ($\hat A$ and $\hat B$) commute if their commutator equals zero.
Extra2:

Lesson: Chapters 3&4
Course: CHEM4502
<!--ID: 1658507444226-->
END

START
Basic-lesson
Front: 
#### Time-Independent Schrodinger Eqn

Back: 

$$\hat H\psi=\left[-\frac{\hbar^{2}}{2m}\frac{d^{2}}{dx^{2}}+V(x)\right]\psi=E\psi$$

Extra1:
Use: The time-independent Schrodinger equation is the basic starting point for determining wavefunctions. We solve for eigenvalues and eigenfunctions of QM operators. Also, the potential energy operator defines a particular QM.
Extra2:
* $\hat H$ = Hamiltonian
Lesson: Chapters 3&4
Course: CHEM4502
<!--ID: 1658507444232-->
END

START
Basic-lesson
Front: 
#### Wavefunction of Particle in 1-D Box Eqn
Back: 

$$\psi(x)= \sqrt{\frac{2}{a}} \sin \frac{n \pi x}{a}$$

Extra1:

Extra2:

Lesson: Chapters 3&4
Course: CHEM4502
<!--ID: 1658507444237-->
END

START
Basic-lesson
Front: 
#### Wavefunction of Particle in 2-D Box Eqn
Back: 

$$\psi(x)= \sqrt{\frac{4}{ab}} \sin \frac{n_{x} \pi x}{a}\sin \frac{n_{y} \pi y}{a}$$

Extra1:

Extra2:

Lesson: Chapters 3&4
Course: CHEM4502
<!--ID: 1658507444242-->
END

START
Basic-lesson
Front: 
#### Wavefunction of Particle in 3-D Box Eqn
Back: 

$$\psi(x)= \sqrt{\frac{8}{abc}} \sin \frac{n_{x} \pi x}{a}\sin \frac{n_{y} \pi y}{a}\sin \frac{n_{y} \pi z}{c}$$

Extra1:

Extra2:

Lesson: Chapters 3&4
Course: CHEM4502
<!--ID: 1658507444247-->
END

START
Basic-lesson
Front: 
#### Energy Eqn of Particle in 1-D Box
Back: 
$$E=\frac{h^{2}}{8m}\left(\frac{n^{2}}{a^{2}}\right)$$
Extra1:

Extra2:

Lesson: Chapters 3&4
Course: CHEM4502
<!--ID: 1658507444253-->
END

START
Basic-lesson
Front: 
#### Energy Eqn of Particle in 2-D Box
Back: 
$$E=\frac{h^{2}}{8m}\left(\frac{n_{x}^{2}}{a^{2}}+\frac{n_{y}^{2}}{b^{2}}\right)$$
Extra1:

Extra2:

Lesson: Chapters 3&4
Course: CHEM4502
<!--ID: 1658507444258-->
END

START
Basic-lesson
Front: 
#### Energy Eqn of Particle in 3-D Box
Back: 
$$E=\frac{h^{2}}{8m}\left(\frac{n_{x}^{2}}{a^{2}}+\frac{n_{y}^{2}}{b^{2}}+\frac{n_{z}^{2}}{c^{2}}\right)$$
Extra1:

Extra2:

Lesson: Chapters 3&4
Course: CHEM4502
<!--ID: 1658507444263-->
END

