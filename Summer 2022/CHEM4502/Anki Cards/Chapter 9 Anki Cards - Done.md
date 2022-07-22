START
Cloze
Front: {{c1::LCAO-MO}} : a means of using atomic orbitals (on different atoms) to construct MOs for the entire molecule; provide approximate solutions to the Schrodinger equation
Back Extra: 
<!--ID: 1658205266993-->
END
START
Cloze
 {{c1::Overlap Integral}}: The degree to which atomic wavefunctions share a portion of the 3-d space
Back Extra: 
<!--ID: 1658205266999-->
END

START
Cloze
Front: {{c1::Coulomb Integral}}: Used to calculate the classical electrostatic interaction energies among charged particles
Back Extra: 
<!--ID: 1658205267005-->
END

START
Cloze
Front: {{c1::Exchange integral}} : Purely QM effect with unknown interpretation-but provide the net energy to make the bonding favorable.
Back Extra: 
<!--ID: 1658205267011-->
END

START
Cloze
Front: 
### Hamiltonian for a Molecule
* {{c1::Can be written by considering all electrostatic interactions||
* {{c1::The Born-Oppenheimer approximation suggests that we can often safely ignore the KE of any/all nuclei}}
* {{c1::Multi-electron systems are still a problem; we use $H^{+}_{2}$ as a solvable, one electron model system for molecules}}
Back Extra: 
<!--ID: 1658205267017-->
END

START
Cloze
Front: 
### Born-Oppenheimer approximation
* {{c1::Nuclei move slow compared to electrons, so we assume they are fixed in space}}
* {{c1::R is a parameter}}
* {{c1::Wavefunctions obtained are not exact, but can be improved iteratively}}
Back Extra: 
<!--ID: 1658205267022-->
END


START
Cloze
Front: 
### Molecular Orbital (MO) Theory
* {{c1::Used to construct molecular wavefunctions }}
* {{c1::similar to the development of H atomic wavefunctions }}
* {{c1::$H^{+}_{2}$ used as a model; solutions are not chemically insightful and are generally not used}}
Back Extra: 
<!--ID: 1658205267028-->
END

START
Cloze
Front: 
 Energy of Wavefunction for a molecule:
 {{c1::
	 $$E=\frac{\int\psi^{*}\hat H\psi dr}{\int\psi^{*}\psi dr}$$
}}
* {{c1::$E_{+}$}} is more stable than separated fragments, leads to chemical bond
* {{c1::$E_{-}$ }}is less stable than separated fragments, does not lead to chemical bond
* {{c1::J}} is repulsive, {{c1::K}} is attractive
* Bonding can only be explained with {{c1::K}}, and is therefore only adequately described by QM
* {{c1::$E_{+}<E_{-}$}}, so ground state has a bond at every R
Back Extra: 
<!--ID: 1658205267034-->
END


START
Cloze
Front: Are multi-electron systems impossible to solve? What to do if so?

{{c1::Yes. we can approximate the solutions of them by using multiple single electron wavefunctions ($H_{2}$ for example)}}

Back Extra: 
<!--ID: 1658205267038-->
END

START
Cloze
Front: Magnetism in context of molecules: {{c1::Unpaired electrons}}
Back Extra: 
<!--ID: 1658205267044-->
END


START
Cloze
Front: 
### Types of MOs
* {{c1::$\sigma$}}: contains electron density on the internuclear axis
* {{c1::$\pi$}}: contains one nodal plane inclusive of internuclear axis
* {{c1::$\delta$}}: contains two nodal planes inclusive of the internuclear axis
* {{c1::Bonding}}: Has no nodal planes perpendicular to the bond axis and between the nuclei
* {{c1::Antibonding}}: Has at least one nodal plane perpendicular to the bond axis and between the nuclei
* {{c1::Nonbonding}}: Do not have AO contributions from both adjacent atoms
* $\sigma_{g}$: bonding, $\sigma_{u}$: Antibonding, $\pi_{g},\delta_{u}$: Antibonding, $\pi_{u},\delta_{g}$: Bonding (Not as important but still deserve a quick glance)
Back Extra: 
![[2022-07-16 08-02-18.excalidraw]]
<!--ID: 1658205267049-->
END
START
Cloze
Front: 
### MO electron configurations of diatomic molecules
* Written based on possible MOs
	* {{c1::Predict bond orders and bond stability, along with trends in bond energy and length}}
	* {{c1::Every MO configuration has its own term symbol}}
	* {{c1::Some excited states are stable, others are dissociative}}
Back Extra: 
<!--ID: 1658205267054-->
END

START
Cloze
Front: 
* Molecular term symbols
	* Similar to atomic term symbols, but for molecules
	* Hund's rules apply to molecules too
	* We generally determine only the {{c1::lowest}} energy molecular term for a given configuration
	* {{c1::$L= 0 \to \Sigma; L= 1 \to \Pi; L= 2 \to \Delta; L= 3 \to \Phi$ }}

Back Extra: 
<!--ID: 1658205267060-->
END

START
Cloze
Front: 
### Homonuclear Diatomics
* {{c1::Two identical}} atoms
* MO energies generally {{c1::increase}} as n {{c1::increases}}
* {{c1::Little/No}} overlap between AOs with different n
* Core orbitals have very little impact on bonding (Focus on valence bonding pretty much)

Back Extra: 
<!--ID: 1658205267065-->
END

START
Cloze
Front: 
### Heteronuclear Diatomics
* {{c1::Two different}} atoms
* MO theory is similar to that for homonuclear diatomics
* Valence orbitals of both atoms usually involved in bonding, core orbitals are not.
Back Extra: 
<!--ID: 1658205267070-->
END

START
Cloze
Front: 
### Energies of 1s-based bonding & anti-bonding in $H^{+}_{2}$
{{c1::
$$E_{\pm}=E_{1s}+\underbrace{\frac{J \pm K}{1\pm S}}_{\text{QM Bonding Energy}}$$

* $K$: Exchange Integral
* $J$: Coulomb Integral
* $S$: Overlap Integral
}}
Back Extra: 
<!--ID: 1658205267076-->
END


START
Cloze
Front: 
### Overlap Integral
Use: {{c1::Measure extent to which wavefunctions share a space}}
$$S=\int_{\text{All space}}\phi^{*}\phi dr$$
### Coulomb Integral
Use: {{c1::Accounts for classical electrostatic interactions (Attractions & repulsions between atoms)}}
$$J=\frac{e^{2}}{4\pi \epsilon_{o}R}-\frac{e^{2}}{4\pi \epsilon_{o}}\int\frac{\phi^{*}_{i}\phi_{i}}{r_{j}}dr$$
### Exchange Integral
Use: {{c1::Accounts for QM interactions to bond energies}}
$$K=\frac{Se^{2}}{4 \pi \epsilon_{o}R}-\frac{e^{2}}{4 \pi \epsilon_{o}}\int\frac{\phi^{*}_{i}\phi_{i}}{r_{j}}dr$$

Back Extra: 
<!--ID: 1658205267082-->
END

START
Cloze
Front: 
### Bond Order
Use: Bond order correlates to bond length and bond energy ($BO \propto \frac{1}{\text{ Bond length}}$, $BO \propto\text{ Bond Energy}$){{c1::
$$BO=\frac{1}{2}[\text{\# bonding electrons}-\text{\# Antibonding electrons}]$$
}}
* Note that $BO >0$ should be stable
Back Extra: 
<!--ID: 1658205267087-->
END

START
Cloze
Front: 
### The Molecular Orbitals $\psi_{+}$ (Bonding) and $\psi_{-}$ (Anti-Bonding) and their squares plotted
{{c1::
![[Chapter 9 - Bonding and Antibonding Plots.png|400]]
}}
Back Extra: 
<!--ID: 1658205267094-->
END




