---
tags: 🧠️/📝️/👨‍🏫/📥️
publish: true
aliases: 
---
# Chapter 13
Created: ### [[2022-06-28]]
___
## Concepts
* Spectroscopy: The predominant means we have to study and understand molecules
___

### Rotational Spectra
* Uses QRR
* Figure:
![[2022-06-28 01-58-02.excalidraw]]
* Transition energies correspond to the difference in energy between two rotational levels.
* The rotational constant describes rotational quantization
* Rotational spectra have lines spaced by (approximately) $2\tilde B$ 
* Rotational analysis can be improved by introducing a centrifugal distortion term
* Selection rules for pure rotational spectra
	* $\Delta J=\pm 1$ (Change in quantum number)
	* Molecule must have a permanent dipole moment


### Polyatomic Rotational Spectra
* Have up to three distinct rotational constants
* Can be analyzed depending on overall molecular geometry
* Can be very complex

### Vibrational Spectra
* Modeled by QHO
* Transition energies correspond to the difference in energy between two vibrational levels.
* The QHO is generally a poor model, which can be corrected by adding anharmonicity constant
* Polyatomic vibrational spectra can be understood as combinations of individual vibrations.
* Most common types: IR and Raman
* IR Selection Rules
	* $\Delta v=\pm 1$
	* Vibration must cause a change in the dipole moment
* Provide a way to measure force constants (Related to bond strength)
* Fundamental frequency: $v=0 \to v=1$ 
* Overtone frequency: $v=0\to v>1$
* Anharmonicity can be modeled with a Morse potential
* Number of Vibrations (Each vibration is unique):
	* Nonlinear molecules: 3N-6
	* Linear molecules: 3N-5
* The potential energy on a molecule is a function of the N vibrations, in case it was not affected by an external field
* If a normal coordinate produced a change in dipole moment, the vibration may be IR active
![[Pasted image 20220629231722.png|350]]
### Rovibrational Spectra
* Display both rotational and vibrational transitions simultaneously
* Have two distinct sets of peaks (Called the R and P branches)
* Modeled using any combination of the following: RR, QHO, Corrected RR, and Corrected QHO
* Usually introduces a constant that accounts for the rotational impact of bond stretching (Rovibrational coupling constant)
* May exert a third (Q) branch for polyatomic molecules
* High frequency side ($\Delta J=+1$): R branch
* Low frequency side ($\Delta J=-1$): P branch
* In pure rotation spectra, $\Delta J =0$ is forbidden, so there is no peak at v itself (Some polyatomic vibrations have a line at v - The Q branch)
* P branch diverges and R branch converges
* Rotational constants depend on the vibrational level.
* Types of bonds:
	* Parallel band: Vibrations occur along the primary molecular axis; normal selection rules apply
	* Perpendicular band: Vibration occurs perp to primary axis; $\Delta J \text{ is allowed}$ 
### Electronic Spectra
* Involve transitions between electron configurations
* Difficult to generally model
* May include vibrational and rotational transitions; Called (Ro)vibronic spectra
* Has intensities governed by Franck-Condon rules
* Include photoelectron spectra, which provide proof for orbitals.
* Rotational spacings are usually too small to observe; vibrational+ electronic = Vibronic spectra
![[Pasted image 20220630020558.png||600]]


### Franck-Condon Intensities
* Electronic transition intensities depend on wavefunction overlap (Including vibrational wfns)
* Large changes in geometry give many vibronic peaks; small changes give few
* Selection rule: No change in the number of unparied electrons
* Vibrations not observed by IR, pure rotational spectroscopy

### Photoelectron Spectroscopy (PES)
* A specific type of elecronic spectroscopy
* (Ro)vibronic data can be still collected
* Measured energy required to remove electrons; allows measurements of ionization energy, electron affinity
* Provides a map of electron energies; experimental basis for existence of orbitals.
* 
### Chapter 13 Equations
#### Rotational Spectra

##### Quantization of Rotational Spectra (QRR)
$$B=\frac{h}{8I\pi^{2}} \to\text{unit is }s^{-1}$$
$$\tilde B=\frac{h}{8cI\pi^{2}} \to\text{unit is }s^{-1}$$


##### Energy Levels
$$\tilde E(J)=\tilde B J(J+1)$$
$$\tilde E(J)=\tilde B J(J+1)-\tilde DJ^{2}(J+1)^{2} \text{\qquad(Correction)}$$


##### Frequency of a (non)rigid  transition depends on the rotational and distortion constant.
$$\tilde v=2\tilde B (J+1)$$
$$\tilde v=\Delta\tilde E=2\tilde B (J+1)-4\tilde D(J+1)^{3} \text{\qquad (Correction)}$$
![[Pasted image 20220629230155.png|450]]
#### Vibrational Spectra (QHO)
##### Energy Levels
$$\tilde E(v)=\tilde v_{e}\left(v+\frac{1}{2}\right)-\color{bblue}\underbrace{\tilde \chi_{e}\tilde v_{e}\left(v+\frac{1}{2}\right)^{2}}_{Correction}$$
##### Frequency of (an)harmonic transition 
Use: Depends on the fundamental frequency $(\tilde v_{e} )$  
$$\tilde v=\tilde v_{e} v-\tilde\chi_{e}\tilde v_{e}v(v+1)$$
* $\tilde\chi_{e}=\text{ Anharmonicity constant}$
![[Pasted image 20220629231628.png|450]]
#### Rovibrational Spectra (Both QHO and QRR)
##### Energy Formula for two transitions
$$\begin{align}
&\Delta \tilde E_{\Delta J=+1}=\tilde E_{R}=\tilde v+2\tilde B(J+1)\\
&=\tilde v+2\tilde B_{1}+(3\tilde B_{1}-\tilde B_{0})J +(\tilde B_{1}-\tilde B_{0})J^{2} \end{align}$$


$$\begin{align*}

&\Delta \tilde E_{\Delta J=-1}=\tilde E_{R}=\tilde v-2\tilde BJ\\
&=\tilde v-(\tilde B_{1}+\tilde B_{0})J +(\tilde B_{1}-\tilde B_{0}) \end{align*}$$



#### Effect of bond lengthening on rotational constant
$$\tilde B_{v}=\tilde B_{e}-\tilde\alpha_{e}(v+\frac{1}{2})$$
#### Rovibronic Spectra
##### Energy of Observed Transition
$$\tilde v_{obs}=\tilde v_{00}+\tilde v_{e}v^{'}-\tilde \chi_{e}\tilde v_{e}v^{'}(v^{'}+1)$$
##### Transition Origin ($\tilde v_{00}$) 
Use: Finding the transition between the two ground vibrational states of two electronic states.
$$\tilde v_{00}=\tilde T_{e}+\frac{1}{2}(\tilde v_{e}^{'}-\tilde v_{e}^{''})-\frac{1}{4}(\tilde \chi_{e}^{'}\tilde v_{e}^{'}-\tilde \chi_{e}^{''}\tilde v_{e}^{''})$$
#### Dissociation Energy of Diatomic Molecule
$$\tilde D_{e}\approx\frac{\tilde v_{e}^{2}}{4\tilde\chi_{e}\tilde v_{e}}$$
$$\tilde D_{0}=\tilde D_{e}-\left(\frac{1}{2}\tilde v_{e}-\frac{1}{4}\tilde \chi_{e}\tilde v_{e}\right)$$
### Examples

**5.7: To a good approximation, the microwave spectrum of $H^{35}Cl$ consists of a series of equally spaced lines, seperated by $6.26\times10^{11}Hz$ . Calculate the bond length of $H^{35}Cl$**

$$\text{Rotational Spectra} $$
$$2B=6.26\times10^{11}s^{-1}\to B=3.13\times10^{11}s^{-1}$$
$$B=\frac{h}{8\pi^{2}I}\to I=\frac{h}{8\pi^{2}B}=2.68\times10^{-47}kgm^{2}$$
$$I=\mu R_{e}^{2}\to R_{e}=\sqrt{\frac{I}{\mu}}=\sqrt{\frac{2.68\times10^{-47}}{\left(\frac{1\times35}{36}\right)\times1.661\times10^{-27}kg/amu}}=1.28\times10^{-10}m=128pm$$
**5.3: The IR spectrum of $^{75}Br^{19}F$ consist of an intense line at $380 cm^{-1}$. Calculate the force constant of that molecule**

$$\Delta E=\tilde v_{obs}=\frac{v}{c}=\frac{\frac{\omega}{2\pi}}{c} =\frac{1}{2\pi c} \sqrt{\frac{k}{\mu}}\to k=(2\pi c v_{obs})^{2}\mu$$
$$k=129kg/s^{2}=129N/m$$
13.6: The frequencies of the first few Vibronic transitions to an excited electronic state of PN are:
![[Pasted image 20220630020842.png|300]]



