---
tags: 🧠️/📝️/👨‍🏫/📥️
publish: true
aliases: 
---
# CHEM4502 - HW5
Created: ### [[2022-07-14]]

Questions: *9-9*, 9-10, *9-13*, *9-14*, *9-19*, *9-23*, *9-30*, *9-34*, *9-36*, *10-2*, *10-6*, 10-19, 10-21

### Chapter 9

**9.9: Show explicitly that an $\color{bred}2s$ orbital on one hydrogen atom and a $\color{bred}2p_{x}$ orbital on another have zero overlap. Use the 2s and 2px wave functions given in Table 6.6 to set up the overlap integral. Take the z axis to lie along the internuclear axis. Hint: You need not evaluate any integrals, but simply show that the overlap integral can be separated into two parts that exactly cancel one another.**

$$\psi_{2s}=\frac{1}{4\sqrt{2 \pi}} \left(\frac{Z}{a_{o}}\right)^{\frac{3}{2}}(2-\sigma)e^{\frac{-\sigma}{2}}$$
$$\psi_{2p_{x}}=\frac{1}{4\sqrt{2 \pi}} \left(\frac{Z}{a_{o}}\right)^{\frac{3}{2}}\sigma e^{\frac{-\sigma}{2}}\sin \theta\cos \phi$$
$$\text{Overlap Integral: }S=\int_{\text{All space}}\psi_{2s}\psi_{2p_{x}} dr$$
$$S=\int_{0}^{2\pi}\cos\phi\int \text{Rest of function}=0$$
**SKIPPED 9.10**


**9-13: Discuss the bond properties of $F_2$ and $F_{2}^{+}$ using molecular-orbital theory.**

![[CHEM4502 - HW5 2022-07-17 09-48-28.excalidraw]]
$$\text{Bond Order: }\begin{align*}
&F_{2}\to BO=\frac{1}{2}(10-8)=1\\
&F_{2}^{+}\to BO=\frac{1}{2}(10-7)=1.5
\end{align*}$$
$$\text{Bond Length: } F_{2}^{+}<F_{2}, \text{ Bond Energy: }F_{2}<F_{2}^{+}$$

**9.14: Predict the relative stabilities of the species $N_2$, $N_{2}^{+}$, and $N_{2}^{-}$.**

![[Chapter9Question14.excalidraw]]

$$\text{Bond Order: }\begin{align*}
&N_{2}\to BO=\frac{1}{2}(10-4)=3\\
&N_{2}^{+}\to BO=\frac{1}{2}(9-4)=2.5\\
&N_{2}^{-}\to BO=\frac{1}{2}(10-5)=2.5
\end{align*}$$
$$\text{Bond Stability } \propto \text{ Bond Order} \to N_{2}>N_{2}^{-}=N_{2}^{+}$$
**9.19: The force constants for the diatomic molecules $B_2$ through $F_2$ are given in the table below. Is the order what you expect? Explain.**

![[CHEM4502 - HW5 - 9.14.png]]

Yes, it is.

![[CHEM4502 - HW5 2022-07-17 10-19-02.excalidraw]]

$$\text{Bond Order: }\begin{align*}
&B_{2}\to BO=\frac{1}{2}(6-4)=1\\
&C_{2}\to BO=\frac{1}{2}(8-4)=2 \\
&N_{2}\to BO=\frac{1}{2}(10-4)=3\\
&O_{2}\to BO=\frac{1}{2}(10-6)=2\\
&F_{2}\to BO=\frac{1}{2}(10-8)=1
\end{align*}$$
$$\text{Bond Stability } \propto \text{ Bond Order}\propto \text{ Force Constant}:$$
$$N_{2}>O_{2}\approx N_{2}>F_{2}\approx B_{2}$$
**9.23: A common light source used in photoelectron spectroscopy is a helium discharge, which generates light at 58.4 nm. A photoelectron spectrometer measures the kinetic energy of the electrons ionized when the molecule absorbs this light. What is the largest electron binding energy that can be measured using this radiation source? Explain how a measurement of the kinetic energy of the ionized electrons can be used to determine the energy of the occupied molecular orbitals of a molecule. Hint: Recall the photoelectron effect discussed in Chapter 1.**

$$E=hv=\frac{hc}{\lambda}=\frac{(6.626\times 10^{-34})(2.998\times10^8)}{58.4\times10^{-9}m}=3.40\times10^{-18}J$$
$$\text{From Chapter 1: }eKE=hv- \phi $$
$$\text{If eKE was measured, and E was just calculated, }\phi \text{ can be found.}$$
$$\to \phi \text{ is the the electron binding energy}$$

**9.30: Deduce the ground-state term symbols of all the diatomic molecules given in Table 9.6.**


|   Molecule   | $M_{l}$-Value | $M_{S}$-Value |        Conclusions        | Molecular Term Symbol |
|:------------:|:-------------:|:-------------:|:-------------------------:|:---------------------:|
| $H_{2}^{+}$  |       0       |      0.5      | $L\to \Sigma, \space S=2$ |     $^{2}\Sigma$      |
|   $H_{2}$    |       0       |       0       | $L\to \Sigma, \space S=1$ |     $^{1}\Sigma$      |
| $He_{2}^{+}$ |       0       |      0.5      | $L\to \Sigma, \space S=2$ |     $^{2}\Sigma$      |
|   $Li_{2}$   |       0       |       0       | $L\to \Sigma, \space S=1$ |     $^{1}\Sigma$      |
|   $B_{2}$    |       0       |       1       | $L\to \Sigma, \space S=3$ |     $^{3}\Sigma$      |
|   $C_{2}$    |       0       |       0       | $L\to \Sigma, \space S=1$ |     $^{1}\Sigma$      |
| $N_{2}^{+}$  |       0       |      0.5      | $L\to \Sigma, \space S=2$ |     $^{2}\Sigma$      |
|   $N_{2}$    |       0       |       0       | $L\to \Sigma, \space S=1$ |     $^{1}\Sigma$      |
| $O_{2}^{+}$  |       1       |      0.5      |  $L\to \Pi, \space S=2$   |       $^{2}\Pi$       |
|   $O_{2}$    |       0       |       1       | $L\to \Sigma, \space S=3$ |     $^{3}\Sigma$      |
|   $F_{2}$    |       0       |       0       | $L\to \Sigma, \space S=1$ |     $^{1}\Sigma$      |

**9.34: For a set of point charges Z,e that lie along a line, we define the dipole moment($\mu$) of the charge distribution by:**
$$\color{bred}\mu =e\sum Z_{i}x_{i}$$
**where e is the protonic charge and $x_{i}$ is the distance of the charge Z,e from the origin. Consider the molecule LiH. A molecular-orbital calculation of LiH reveals that the bond length of this diatomic molecule is 159 pm and that there is a net charge of +0.76e on the lithium atom and a net charge of -0.76e on the hydrogen atom. First, determine the location of the center-of-mass of the LiH molecule. Use the center-of-mass as the origin along the x-axis and determine the dipole moment of the LiH molecule. How does your value compare with the experimental value of $\color{bred}19.62 \times 10^{-30}C\space m$**

$$\text{Given that we know the distance from the center of mass is equal for both:}$$
$$D_{Li}=D_{H}\to m_{Li}x=m_{H}(D-x) \to \text{Solve for x}$$
$$x=\frac{159pm}{(1+\frac{6.941}{1.008})}=20.1625\approx20.163 pm$$
$$\mu =e\sum Z_{i}x_{i}=e[(0.76)(20.163)-\underbrace{[-(0.76)(159-20.163)]]}_{\text{Negative due to H being in -x-axis}}$$
$$\mu =e\times1.2084 \times10^{-10}m=(1.6\times10^{-19}C)(1.2084\times10^{-10}m)$$
$$\mu =1.93344\times10^{-29}\to19.3344\times10^{-30}C \space m$$
$$\therefore\text{The calculated value is really close to the experimental value provided.}$$

**9.36: What would be the value of the dipole moment of LiH if its bond were purely ionic? Estimate the amount of ionic character in LiH. (See Problem 9-34).**

$$\mu_{theo} =e\sum Z_{i}x_{i}=e[(1)(20.163\times10^{-12}m)+(1)(159\times10^{-12}- 20.163\times10^{-12}m)]$$
$$\mu_{theo} =2.544\times10^{-29}C \space m,\mu_{obs}=1.93344\times10^{-29}C \space m$$
$$\text{\% Ionic Character: }\frac{\mu_{obs}}{\mu_{theo}}\times100\%=\frac{1.93344\times10^{-29}C \space m}{2.544\times10^{-29}C \space m}\times100\%$$
$$\text{\% Ionic Character = }76\%$$

### Chapter 10

**10.2: Show that the three $sp^2$ hybrid orbitals given by Equations 10.3 through 10.5 are normalized.**

$$\psi_{1}=\frac{1}{\sqrt{3 }}2s+\sqrt{\frac{2}{3 }}2p_{z}$$
$$\psi_{2}=\frac{1}{\sqrt{3 }}2s-\frac{1}{\sqrt{6 }}2p_{z}+\frac{1}{\sqrt{2 }}2p_{x}$$
$$\psi_{3}=\frac{1}{\sqrt{3 }}2s-\frac{1}{\sqrt{6 }}2p_{z}-\frac{1}{\sqrt{2 }}2p_{x}$$
$$\text{To show normalization: }\int\psi^{\star}\psi=1$$
$$\psi_{1}\to\int\psi^{\star}\psi=\int\left[\frac{1}{\sqrt{3 }}2s^{\star}+\sqrt{\frac{2}{3 }}2p_{z}^{\star}\right]\left[\frac{1}{\sqrt{3 }}2s+\sqrt{\frac{2}{3 }}2p_{z}\right]d\tau$$
$$=\frac{1}{3}\int2s^{\star}2sd\tau+\frac{\sqrt{2}}{3}\int(2s^{\star}2p_{z}+2p_{z}^{\star}2s)d\tau+\frac{2}{3}\int2p_{z}^{\star}2p_{z}d\tau$$
$$\text{From Chapter 8 in textbook: }\begin{align*}
&\int \alpha^{*}(\sigma)\alpha(\sigma)d \sigma=\int \beta^{*}(\sigma)\beta(\sigma)d \sigma=1\\
&\int \alpha^{*}(\sigma)\beta(\sigma)d \sigma=\int \alpha(\sigma)\beta^{*}(\sigma)d \sigma=0
\end{align*}$$
$$=\frac{1}{3}+\frac{2}{3}=1$$
$$\psi_{2}\to \int\left[\frac{1}{\sqrt{3 }}2s^{\star}-\frac{1}{\sqrt{6 }}2p_{z}^{\star}+\frac{1}{\sqrt{2 }}2p_{x}^{\star}\right]\left[\frac{1}{\sqrt{3 }}2s-\frac{1}{\sqrt{6 }}2p_{z}+\frac{1}{\sqrt{2 }}2p_{x}\right]d\tau$$
$$=\left(\frac{1}{3}\int2s^{\star}2s-\frac{1}{\sqrt{18}}\int2s^{\star}2p_{z}=\frac{1}{\sqrt{6}}\int2s^{\star}2p_{x}\right)+\left(-\frac{1}{\sqrt{18}}\int2p_{z}^{\star}2s+\frac{1}{6}\int2p_{z}^{\star}2p_{z}-\frac{1}{\sqrt{12}}\int2p_{z}^{\star}2p_{x}\right)$$
$$+\left(\frac{1}{\sqrt{6}}\int2p_{x}^{\star}2s-\frac{1}{\sqrt{12}}\int2p_{x}^{\star}2p_{z}+\frac{1}{2}\int2p_{x}^{\star}2p_{x}\right)=\frac{1}{3}+\frac{1}{6}+\frac{1}{2}=1$$
$$\psi_{3}\to \psi_{2}\to \int\left[\frac{1}{\sqrt{3 }}2s^{\star}-\frac{1}{\sqrt{6 }}2p_{z}^{\star}-\frac{1}{\sqrt{2 }}2p_{x}^{\star}\right]\left[\frac{1}{\sqrt{3 }}2s-\frac{1}{\sqrt{6 }}2p_{z}-\frac{1}{\sqrt{2 }}2p_{x}\right]d\tau$$

$$=\left(\frac{1}{3}\int2s^{\star}2s-\frac{1}{\sqrt{18}}\int2s^{\star}2p_{z}-\frac{1}{\sqrt{6}}\int2s^{\star}2p_{x}\right)+\left(-\frac{1}{\sqrt{18}}\int2p_{z}^{\star}2s+\frac{1}{6}\int2p_{z}^{\star}2p_{z}+\frac{1}{\sqrt{12}}\int2p_{z}^{\star}2p_{x}\right)$$
$$+\left(\frac{1}{\sqrt{6}}\int2p_{x}^{\star}2s-\frac{1}{\sqrt{12}}\int2p_{x}^{\star}2p_{z}+\frac{1}{2}\int2p_{x}^{\star}2p_{x}\right)=\frac{1}{3}+\frac{1}{6}+\frac{1}{2}=1$$

**10.6: Given that one sp hybrid orbital is**
$$\color{bred}\xi_{1}=\frac{1}{\sqrt{2 }} (2s+2p_{z})$$
**construct a second one by requiring that it be normalized and orthogonal to $\xi_{1}$ .**

$$\xi_2=c_{1}2s+c_{2}2p_{z}$$
$$\int\xi_{1}^{\star}\xi_2=0,\int\xi_{2}^{\star}\xi_{2}=1$$
$$\int\xi_{1}^{\star}\xi_{2}=\int\left(\frac{1}{\sqrt{2}}2s^{\star}\right)(c_{1}2s)+\int\left(\frac{1}{\sqrt{2}}2p_{z}^{\star}\right)(c_{2}2p_{z})=0$$
$$=\frac{1}{\sqrt{2 }}c_{1}(1)+\frac{1}{\sqrt{2}}(1)=0\to c_{1}=-c_{2}$$
$$\int\xi_{2}^{\star}\xi_{2}=\int (-c_{2}2s^{\star}+c_{2}2p_{z}^{\star})(-c_{2}2s+c_{2}2p_{z})=1$$
$$=\int c_{2}^{2}2s^{\star}2s+\int c_{2}^{2}2p^{\star}_{z}2p_{z}=c_{2}^{2}(1)+c_{2}^{2}(1)=1\to=2c_{2}^{2}=1$$
$$c_{2}=\frac{1}{\sqrt{2}},c_{1}=-\frac{1}{\sqrt{2}}$$
$$\xi_{2}=-\frac{1}{\sqrt{2 }}2s+\frac{1}{\sqrt{2}}2p_{Z}$$
