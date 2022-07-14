---
tags: 🧠️/📝️/👨‍🏫/📥️
publish: true
aliases: 
---
# Chapter 8
Created:  [[2022-07-07]]

## Concepts
* [[#Spin]]
* [[#Antisymmetry]]
* [[#Postulate 6]]
* [[#Term symbols]]
* [[#Hund's Rules]]
* [[#Atomic Spectra]]



### Spin
* Electrons have an inherent, fundamental angular momentum which we call "spin"
* The length and z-axis projection of the spin vector are quantized; the z-axis projection gives a fourth quantum number; $m_{s}$ (Note that $m_{l}$ is used for z component of orbital angular momentum)
* Spin add another contribution to the H atom wavefunction
* Spin is necessary for describing multielectron systems
* There must be operators, eigenfunctions for spin
* We do not know their forms, only the associated eigenvalues
* Spin has no classical analog; it is purely QM Effect
* 

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
* Selection rules:
	* $\Delta L=\pm 1$
	* $\Delta S=0$
	* $\Delta J=0, \pm 1$ except (J=0 to J=0)
* Lines in H spectra are actually doublets
* Small splitting are called fine structure.

### Chapter 8 Eqns

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
### Figures
* ![[Pasted image 20220707073306.png|500]]

* Notation for spin wavefunctions:![[2022-07-07 07-43-53.excalidraw|75]]



* Smiley face:
![[Pasted image 20220710055117.png|100]]

### Examples:
**Q: What are all of the term symbols for the first excited state of He?**

$$\text{First excited state of He: }1s^{1}2s^{1}$$
$$\text{First, we need to find how the microstates:}$$
$$=\frac{2!}{1!(2-1)!} \times\frac{2!}{1!(2-1)!}=2\times2=4$$
$$\text{Microstates:}$$
![[2022-07-07 09-11-48.excalidraw]]

$$\text{Another way to write them: }(0^{+},0^{+}),(0^{-},0^{+}),(0^{+},0^{-}),(0^{-},0^{-}) \space \text{where 0 is L and the sign is spin}$$

  |     | L\S | 1               |               0                |       -1        |
  | --- | --- | --------------- |:------------------------------:|:---------------:|
  |     | 0   | $(0^{+},0^{+})$ | $(0^{+},0^{-}), (0^{-},0^{+})$ | $(0^{-},0^{-})$ |
$$\text{Term Symbols: }
\begin{align*}
& \text{1st Term } \to \text{Up and Left Most} \to l=0=S ,S=2(1)+1=3,J=1,^{3}S_{1}\\
& \text{2nd Term } \to \text{Second Column} \to l=0=S ,S=2(0)+1=1,J=0,^{1}S_{0}\\

\end{align*}$$
$$\text{To check the number of entries being crossed: } (2S+1)(2L+1)=\text{Number of Microstates Crossed}$$



### In-Class Problems

**8.1: Write the correct antisymmetric wavefunction for boron, which has an electron configuration of $\color{bred}1s^{2} 2s^{2} 2p^{1}$** 

$$\Psi = \frac{1}{\sqrt{5!}}
\begin{vmatrix}(\psi_{1})_{1} & (\psi_{2})_{1} & \dots & (\psi_{N})_{1} \\ (\psi_{1})_{2} & (\psi_{2})_{2} & \dots & (\psi_{N})_{2} \\ (\psi_{1})_{1} & (\psi_{2})_{1} & \ddots & \vdots  \\ (\psi_{1})_{N} & (\psi_{2})_{N} & \dots & (\psi_{N})_{N}\end{vmatrix}$$

$$\Psi = \frac{1}{\sqrt{5!}}
\begin{vmatrix}(\psi_{1s}\alpha)_{1} & (\psi_{1s}\beta)_{1} & (\psi_{2s}\alpha)_{1} & (\psi_{2s}\beta)_{1} & (\psi_{2p}\alpha)_{1} \\ (\psi_{1s}\alpha)_{2} & (\psi_{1s}\beta)_{2} & (\psi_{2s}\alpha)_{2} & (\psi_{2s}\beta)_{2} & (\psi_{2p}\alpha)_{2} \\ (\psi_{1s}\alpha)_{3} & (\psi_{1s}\beta)_{3} & (\psi_{2s}\alpha)_{3} & (\psi_{2s}\beta)_{3} & (\psi_{2p}\alpha)_{3}   \\ (\psi_{1s}\alpha)_{4} & (\psi_{1s}\beta)_{4} & (\psi_{2s}\alpha)_{4} & (\psi_{2s}\beta)_{4} & (\psi_{2p}\alpha)_{4}  \\ (\psi_{1s}\alpha)_{5} & (\psi_{1s}\beta)_{5} & (\psi_{2s}\alpha)_{5} & (\psi_{2s}\beta)_{5} & (\psi_{2p}\alpha)_{5} \end{vmatrix}$$

**8.2: Which of the following transitions are allowed in the normal electronic emission spectrum of an atom? For those which are not allowed, explain why.**
$$\color{bred}\begin{align*}
& a) ^{2}D_\frac{3}{2}\to \space^{2}S_\frac{1}{2}\\
&b) ^{1}D_{0}\to \space^{1}S_0\\
&c) ^{3}P_0\to \space^{3}S_1\\
&a) ^{3}D_3\to \space^{1}D_1
\end{align*}$$

a) $$ \text{Conditions: }\begin{align*}
	&\Delta L=\pm 1  \qquad \text{False}\\
	&\Delta S=0 \\
	&\Delta J=0, \pm 1 \text{ except (J=0 to J=0)} 
\end{align*}$$
$$\boxed{\therefore \text{This is not an allowed transition}}$$
b)$$ \text{Conditions: }\begin{align*}
	&\Delta L=\pm 1  \qquad \text{False}\\
	&\Delta S=0 \\
	&\Delta J=0, \pm 1 \text{ except (J=0 to J=0)}
\end{align*}$$
$$\boxed{\therefore \text{This is not an allowed transition}}$$
c) $$ \text{Conditions: }\begin{align*}
	&\Delta L=\pm 1  \qquad \text{True}\\
	&\Delta S=0 \qquad \text{True}\\
	&\Delta J=0, \pm 1 \text{ except (J=0 to J=0)} \qquad \text{True}
\end{align*}$$
$$\boxed{\therefore \text{This is an allowed transition}}$$
d) $$ \text{Conditions: }\begin{align*}
	&\Delta L=\pm 1  \qquad \text{False}\\
	&\Delta S=0 \\
	&\Delta J=0, \pm 1 \text{ except (J=0 to J=0)}
\end{align*}$$
$$\boxed{\therefore \text{This is not an allowed transition}}$$

**9.1: What information is contained in the term symbol $\color{bred}^{2}D_\frac{3}{2}$ ?**

$$\begin{align*}
& \text{1. Total Orbital Angular Momentum } (l)=2 \space \text{if D}\\
&\text{2. Spin Multiplicity = Doublet } \\
&\text{3. Russell-Saunders Coupling (J) = } \frac{3}{2}\\
& \text{4. Total Spin Angular Momentum (S) = } \frac{1}{2}
\end{align*}$$


