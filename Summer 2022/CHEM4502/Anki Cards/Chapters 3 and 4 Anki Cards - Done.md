START
Cloze
**Orthogonality**: {{c1::The cross product of linearly independent vectors is zero.}}
Back Extra: 

END


START
Cloze
**Orthonormal** **vectors**: {{c1::Vectors that are both normalized and orthogonal. Sets of wavefunctions are orthonormal.}}
Back Extra: 

END

START
Cloze
**Commutators**: {{c1::A mathematical check whether the order of operations matter. Also, operators commute if their eigenvalues can simultaneously be measured.}}
Back Extra: 

END

START
Cloze
The eigenfunctions, or wavefunctions, allow for {{c1::predictions to be made about physical observables according to postulates.}}
Back Extra: 

END

START
Cloze
**Correspondence Principle**: {{c1::Quantum Mechanics results must match macroscopic observations when applied to micro systems.}}
Back Extra: 

END

START
Cloze
**Tunneling**: {{c1::Existence of Quantum Mechanics' particles in classically forbidden regions}}
Back Extra: 

END

START
Cloze
**Observable**: {{c1::Something measurable}}
Back Extra: 

END

START
Cloze
**Operator**: {{c1::Performs a mathematical operation on a function}}
Back Extra: 

END

START
Cloze
 Linear Operator (Hamilitan) ={{c1:: $\hat A(f+g)= \hat A f+ \hat A g$ }}
Back Extra: 

END

START
Cloze
#### Postulate 1
Statement: {{c1::There is a wavefunction $(\psi(\boldsymbol{x}))$  for any Quantum Mechanics system.}}
Conditions:
* The wavefunction is a {{c1::solution}} to a wave equation
* The wavefunction must be {{c1::well-behaved (Normalized)}} over its allowed interval (Particle must be {{c1::**somewhere**}} in the allowed space)
	* {{c1:: $\psi(\boldsymbol x),\psi^{'}(\boldsymbol x)$ must be single-valued }}
	* {{c1:: $\psi(\boldsymbol x),\psi^{'}(\boldsymbol x)$ must be continuous}}
	* {{c1:: $\psi(\boldsymbol x),\psi^{'}(\boldsymbol x)$ must be finite}}
	* {{c1:: $\psi(\boldsymbol x)$ must approach 0 as $\boldsymbol x \to \pm \infty$ }} 
* The probability the particle for a quantum mechanics system lies between $x$ and $x+dx$ is related to {{c1:: $\psi^{*}(\boldsymbol{x})\psi(\boldsymbol{x})dx$ }}
* Can be extended to {{c1::multi}}-particle systems.

Back Extra: 

END


START
Cloze
#### Postulate 2
Statement: {{c1::There are operators for all physical observables}}
Back Extra: 

END

START
Cloze
#### Postulate 3
Statement: {{c1::The operators have eigenvalues, and physical observables take values which are eigenvalues of their operators.}}
Condition:
* The {{c1::eigenvalue $a$ }} of an eigenfunction $(\psi(x))$ for an operator $\hat A$ obeys: 
{{c1:: $\hat A \psi(x)=a\psi(x)$ }}
* Wavefunctions may be imaginary/complex; Observables must be{{c1:: real.}}
* QM operators must be {{c1::Hermitian}}, because eigenvalues of Hermitian operators must be {{c1::real}}.

Back Extra: 

END

START
Cloze
#### Postulate 4
Statement: {{c1::The average (or expected) value of an operator's eigenvalue can be determined if the normalized wavefunction is known.}}
Condition:
* {{c1::The operator must be inserted into the distribution function in the proper location: $$\langle a \rangle =\int_{\textrm{all space}} \psi^{*}\hat A \psi\ dx=a\int_{\textrm{all space}} \psi^{*} \psi\ dx=a(1)=a$$
}}
Back Extra: 

END

START
Cloze
#### Postulate 5
Statement: {{c1::Wavefunctions may evolve over time. However, in this course we are interested only in stationary states (do not change over time).}}

Back Extra: 

END

START
Cloze
### Particle in a 1-D Box
Figure: {{c1::

![[2022-06-17 05-53-57.excalidraw]]

}}
Conditions:{{c1::
* $\psi(0)=\psi(a)=0$
}}
Back Extra: 

END

START
Cloze
#### Solutions' Figure for 1-d Particle in Box 
{{c1::
![[Pasted image 20220617190134.png]]
* $Nodes=n-1$ 
* $P=\psi^{*}\psi=\psi^{2}$ 

}}
Back Extra: 

END

START
Cloze
### 2-D Particle in Box
#### Figure:
{{c1::
![[2022-06-17 19-20-18.excalidraw]]
}}
#### Equation: 
{{c1::
$$\psi(x)= \sqrt{\frac{4}{ab}} \sin \frac{n_{x} \pi x}{a}\sin \frac{n_{y} \pi y}{a}$$
}}
Back Extra: 

END

## Eqns

START
Cloze
#### Postulate 1 Equation
Use: {{c1::Provides a valid statistical distribution from the wavefunction
$$p(\boldsymbol x)dx=\psi^{*}(\boldsymbol{x})\psi(\boldsymbol{x})d\boldsymbol x$$
* $\psi^{*}$ = Complex conjugate of $\psi$ (Replace the sign of the $i$ part in the function. That's it)

}}
Back Extra: 

END

START
Cloze
#### Operator Effect on Functions
Use: {{c1:: An operator acts on a function to give a new function
$$\hat A f(x)=g(x)$$

}}
Back Extra: 

END

START
Cloze
#### Postulate 2's Equation
Use: {{c1::An operator, its eigenfunctions, and the eigenvalues are defined by a specific relationship.
$$\hat A f(x)=af(x)$$
* $a$=Eigenvalue
* $f(x)$ = Eigenfunction of $\hat A$
}}
Back Extra: 

END

START
Cloze
#### Wavefunctions' Orthonormality
Use: {{c1::Wavefunctions satisify orthonormality.
$$\int_{\textrm{all space}}\psi^{*}_{i}\psi_{j}d\vec{x}=\delta_{ij}\begin{cases}
=0,\ \ i\neq j \\
=1,\ \ i=j
\end{cases}$$
* $\delta_{ij}$ :  Kronecker delta function
* if $\int_\textrm{all space}\psi_{i}^{*}\psi_{j}=0$ then $i\neq j$  
* if $\int_\textrm{all space}\psi_{i}^{*}\psi_{j}=1$ then $i=j =i$   
}}
Back Extra: 

END

START
Cloze
#### Operators' Commutation Eqn
Use: {{c1::Two operators ($\hat A$ and $\hat B$) commute if their commutator equals zero.
$$[\hat A, \hat B ]f=\hat B \hat Af-\hat A\hat B f$$

}}
Back Extra: 

END

START
Cloze
#### Time-Independent Schrodinger Eqn
Use: {{c1:: The time-independent Schrodinger equation is the basic starting point for determining wavefunctions. We solve for eigenvalues and eigenfunctions of QM operators. Also, the potential energy operator defines a particular QM.
$$\hat H\psi=\left[-\frac{\hbar^{2}}{2m}\frac{d^{2}}{dx^{2}}+V(x)\right]\psi=E\psi$$
* $\hat H$ = Hamiltonian
}}
Back Extra: 

END

START
Cloze
#### Wavefunction of Particle in 1-D Box
{{c1::
$$\psi(x)= \sqrt{\frac{2}{a}} \sin \frac{n \pi x}{a}$$
}}
#### Wavefunction of Particle in 2-D Box
{{c1::
$$\psi(x)= \sqrt{\frac{4}{ab}} \sin \frac{n_{x} \pi x}{a}\sin \frac{n_{y} \pi y}{a}$$
}}
#### Wavefunction of Particle in 3-D Box
{{c1::
$$\psi(x)= \sqrt{\frac{8}{abc}} \sin \frac{n_{x} \pi x}{a}\sin \frac{n_{y} \pi y}{a}\sin \frac{n_{y} \pi z}{c}$$
}}
Back Extra: 

END

START
Cloze
#### Energies' Eqns of Particles in Boxes:
1-D Box:
{{c1::
$$E=\frac{h^{2}}{8m}\left(\frac{n^{2}}{a^{2}}\right)$$
}}
2-D Box:
{{c1::
$$E=\frac{h^{2}}{8m}\left(\frac{n_{x}^{2}}{a^{2}}+\frac{n_{y}^{2}}{b^{2}}\right)$$
}}
3-D Box:
{{c1::

$$E=\frac{h^{2}}{8m}\left(\frac{n_{x}^{2}}{a^{2}}+\frac{n_{y}^{2}}{b^{2}}+\frac{n_{z}^{2}}{c^{2}}\right)$$
}}
Back Extra: 

END

