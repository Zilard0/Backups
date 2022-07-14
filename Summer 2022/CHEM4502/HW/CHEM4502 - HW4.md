---
tags: 🧠️/📝️/👨‍🏫/📥️
publish: true
aliases: 
---
# CHEM4502 - HW4
Created:  [[2022-07-07]]
___

### Chapter 6
**6.7: Show that the first few associated Legendre functions given in Table 6.2 are solutions to Equation 6.23 and that they satisfy the orthonormality condition, Equation 6.28.**

$$(1-x^{2})\left(\frac{d^{2}P}{dx^{2}}\right)-2x \frac{dP}{dx}+\left[l(l+1)-\frac{m^{2}}{1-x^{2}}\right]P(x)=0 \qquad \text{Eqn 6.23}$$
$$\int_{-1}^{1} P_{l}^{|m|}(x)P_{n}^{|m|}(x)dx=\int_{0}^{\pi}P_{l}^{|m|}(\cos \theta)P_{n}^{|m|}(\cos \theta) \sin \theta d \theta $$
$$= \left[\frac{\left(2\right)}{2l+1}\frac{(l+|m|)!}{(l-|m|)!}\right]\delta_{ln} \qquad \text{Orthonormality condition} $$
$$\text{First few solutions : }
\begin{align*}
& P^{0}_{0} (x)=1\\
&P^{0}_{1} (x)=x=\cos \theta\\
&P^{1}_{1} (x)= (1-x^{2})^{\frac{1}{2}}=\sin \theta
\end{align*}
$$

$$\text{At } P^{0}_{0}(x)=1 \to (1-x^{2})(0)-2x(0)+[0(1)-0](1)=0$$
$$\text{At } P^{0}_{1}(x)\to (1-x^{2})(0)-2x(1)+[1(2)-0](x)=-2x+2x=0$$
$$\text{At } P^{1}_{1}(x) \to (1-x^{2})(\frac{-1}{\sqrt{1-x^{2}}}\frac{x^{2}}{\sqrt[\frac{3}{2}]{1-x^{2}}})-2x(\frac{-x}{\sqrt{1-x^{2}}})+\left[1(2)-\frac{1}{1-x^{2}}\right](\sqrt{1-x^{2}})=0$$
$$\text{Using the orthonromality condition:}$$
$$\begin{align*}
&\text{For }P^{0}_{0} \to \int_{-1}^{1}P_{0}^{0}P_{0}^{0}dx=\frac{2}{1}\frac{0!}{0!}=2\\
&\text{For }P^{0}_{1} \to \int_{-1}^{1}P_{1}^{0}P_{1}^{0}dx=\frac{2}{3}\frac{1!}{1!}= \frac{2}{3}\\
&\text{For }P^{0}_{0} \text{ and } P_{1}^{0}\to \int_{-1}^{1}P_{0}^{0}P_{1}^{0}dx=\int_{-1}^{1}xdx=\left[\frac{x^{2}}{2}\right]^{1}_{-1} =0
\end{align*}$$

$$\therefore \text{They satsify the orthonormality condition}$$

**6.15: For an isolated hydrogen atom, why must the angular momentum vector L lie on a cone that is symmetric about the z-axis? Can the angular momentum operator ever point exactly along the z-axis?**

The reasoning behind cone shape is that the x- and y- axis projections of the angular momentum vector are unknowable, which leaves us with a circular shape, in this case being a cone. No, the angular momentum cannot lie along the z-axis, due to the fact that this will violate what was mentioned before, where we will be able to infer the values of the x- and y- projections.



**6.28: Calculate the value of (r) for the n = 2, l = 1 state and the n = 2, l = 0 state of the hydrogen atom. Are you surprised by the answers? Explain.**

$$\left<r\right>=\underbrace{\int_{0}^{2\pi}}_\phi\underbrace{\int_{0}^{\pi}}_\theta\underbrace{\int_{0}^{r}}_{r} \psi ^{*}r\psi r^{2}dr\sin(\theta)d\theta d\phi$$
$$\left<r_{21}\right>=\int_{0}^{2\pi}\int_0^{\pi}\int_{0}^{\infty}\left[\frac{1}{4\sqrt{2\pi}}\left(\frac{1}{a_{0}}\right)^{\frac{3}{2}} \left(\frac{r}{a_{o}} \right)e^{-\frac{r}{2a_{0}}}\cos \theta\right] ^{2}r^{3}dr\sin \theta d \theta  d \phi$$
$$=\frac{1}{32 \pi}\left(\frac{1}{a_{o}}\right)^{3}\left(\frac{1}{a_{o}} \right)^{2}(2 \pi)\left(\frac{2}{3}\right)\int_{0}^{\infty}r^{5}e^{\frac{-r}{a_{o}}}dr=5a_{o}$$
$$\left<r_{20}\right>=\int_{0}^{2\pi}\int_0^{\pi}\int_{0}^{\infty}\left[\frac{1}{4\sqrt{2\pi}}\left(\frac{1}{a_{0}}\right)^{\frac{3}{2}} \left(2-\frac{r}{a_{o}} \right)e^{-\frac{r}{2a_{0}}}\right] ^{2}r^{3}dr\sin \theta d \theta  d \phi$$
$$=\frac{1}{32 \pi}\left(\frac{1}{a_{o}}\right)^{3}\left(\frac{1}{a_{o}} \right)^{2}(2 \pi)\left(2\right)\int_{0}^{\infty}r^{3}\left(2-\frac{r}{a_{o}}\right)^{2}e^{\frac{-r}{a_{o}}}dr=5a_{o}$$
$$\text{Integral Part (Expand and Seperate):}$$
$$\int_{0}^{\infty}4r^{3}e^\frac{-r}{a_{o}}-\int_{0}^{\infty}\left(\frac{4r^{3}}{a_{o}}\right)e^\frac{-r}{a_{o}}+\int_{0}^{\infty}r^{3}\left(\frac{r}{a_{o}}\right)^{2}e^\frac{-r}{a_{o}}$$
$$\text{Integration by Parts and multiply by constants:}$$
$$=3a_{o}-12a_{o}+15a_{o}=6a_{o}$$
The results are surprising, for It was expected that the p-orbital will be further away from the s-orbital instead of the opposite.



**6.40: The average value of $r^2$ for a hydrogenlike atom can be evaluated in general and is given by:** 
$$\color{bred}\left<r^{2}\right>_{nl} =\frac{n^{4}a_{o}^{2}}{Z^{2}}\left[1+\frac{3}{2}\left[1-\frac{l(l+1)-\frac{1}{3}}{n^{2}}\right]\right]$$
**Verify this formula explicitly for the $\color{bred}\psi_{210}$ orbital**


$$\text{Using the equation: }\left<r^{2}\right>_{21}=\frac{16a_{o}^{2}}{Z^{2}}\left[1+\frac{3}{2}\left[\frac{7}{12}\right]\right]=\frac{30a_{o}^{2}}{Z^{2}} $$
$$\text{The other method is using the general method of finding the radius: }$$
$$\left<r^{2}\right>_{21}=\int_{0}^{2\pi}\int_0^{\pi}\int_{0}^{\infty}\left[\frac{1}{\sqrt{32\pi}}\left(\frac{Z}{a_{0}}\right)^{\frac{3}{2}} \left(\frac{Zr}{a_{o}} \right)e^{-\frac{Zr}{2a_{0}}}\cos \theta\right] ^{2}r^{4}dr\sin \theta d \theta  d \phi$$


$$\left<r^{2}\right>_{21}=\left(\frac{1}{32\pi}\right)(2\pi)\left(\frac{2}{3}\right)\left(\frac{Z}{a_{o}}\right)^{3}\int_{0}^{\infty}\left[ \left(\frac{Zr}{a_{o}} \right)e^{-\frac{Zr}{2a_{0}}}\right] ^{2}r^{4}dr $$
$$=\left(\frac{1}{32\pi}\right)(2\pi)\left(\frac{2}{3}\right)\left(\frac{Z}{a_{o}}\right)^{3}\left(\frac{720a_{o}^{5}}{Z^{5}}\right)=\frac{30a^{2}_{o}}{Z^{2}}$$

**6.46: Equation 1 of Problem 6-45 shows that a state with given values of n and l is split into $2l + 1$ levels by an external magnetic field. For example, Figure 6.8 shows the results for the1s and 2p states of atomic hydrogen. The 1s state is not split $(2l + 1 = 1)$, but the 2p state is split into three levels $(2l + 1 = 3)$. Figure 6.8 also shows that the 2p to 1s transition in atomic hydrogen could (see Problem 6-47) be split into three distinct transitions instead:**
![[Pasted image 20220709085008.png|400]]
**of just one. Superconducting magnets have magnetic field strengths of the order of 15 T. Calculate the magnitude of the splitting shown in Figure 6.8 for a magnetic field of 15 T. Compare your result with the energy difference between the unperturbed 1s and 2p levels. Show that the three distinct transitions shown in Figure 6.8 lie very close together. We say that the 2p to 1s transition that occurs in the absence of a magnetic field becomes a triplet in the presence of the field. The occurrence of such multiplets when atoms are placed in magnetic fields is known as the Zeeman effect.**

$$\Delta E=[E_{o}+E_{B}]_{f}-[E_{o}+E_{B}]_{i}=E_{B,f}-E_{B,i}=m_{f,l}\beta B-m_{i,l}\beta B$$
$$m_{f}=0,m_{i}=0,\pm1 \to \Delta E=0 J \text{ or }\Delta E=\pm (1)(9.274\times10^{-24} JT^{-1} )(15T)= \pm 1.3911\times10^{-22} J $$
$$\text{Note that the negative value will ignored because we are only looking for the magnitude.}$$
$$\text{Energy Difference between 1s and 2p: }E=(1)^{2}(1.09737\times10^{5}cm^{-1})\left[\frac{1}{1}-\frac{1}{2^{2}}\right]$$
$$=82302.8cm^{-1}=1.635\times10^{-18} J$$
$$\therefore\text{The value of the change in energy is much smaller compared to the energy difference, }$$
$$\text{Thus, the transition are close to each other.}$$


**6.47: Consider a transition between the l = 2 and the l = 3 states of atomic hydrogen. What is the total number of conceivable transitions between these two states in an external magnetic field? For light whose electric field vector is parallel to the direction of the external magnetic field, the selection rule is $\color{bred}\Delta m = 0$. For light whose electric field vector is perpendicular to the direction of the external magnetic field, the selection rule is $\color{bred}\Delta m = ± 1$. In each case, how many of the possible transitions are allowed?**


$$\text{For }l=2,l=3, \text{ there are a total of 5 and 7 transition states respectively, totaling to 35 different transitions }$$


### Chapter 8 


**8.16: Why is it impossible to distinguish the two electrons in a helium atom, but not the two electrons in separated hydrogen atoms? Do you think the electrons are distinguishable in the diatomic $H_2$ molecule? Explain your reasoning.**

For the helium atom, that is due to the fact that electrons in a system cannot be distinguished (Indistinguishability); we must consider all possible arrangements, which boils down to the antisymmetry concept. On the other hand, the separated hydrogen atoms are two separate systems, hence the two electrons are independent from each other. However, the diatomic hydrogen molecule is one system, which implies that the electrons will be indistinguishable


**8.19: Show that the atomic determinantal wave function**
$$\color{bred}\psi=\frac{1}{\sqrt{2 }}
\begin{vmatrix}1s \alpha(1) & 1s \beta(1) \\ 1s \alpha(2) & 1s \beta(2)\end{vmatrix}$$
**is normalized if the 1s orbitals are normalized**



$$\text{From Chapter 8 in textbook: }\begin{align*}
&\int \alpha^{*}(\sigma)\alpha(\sigma)d \sigma=\int \beta^{*}(\sigma)\beta(\sigma)d \sigma=1\\
&\int \alpha^{*}(\sigma)\beta(\sigma)d \sigma=\int \alpha(\sigma)\beta^{*}(\sigma)d \sigma=0
\end{align*}$$
$$\psi=\frac{1}{\sqrt{2 }}
\begin{vmatrix}1s \alpha(1) & 1s \beta(1) \\ 1s \alpha(2) & 1s \beta(2)\end{vmatrix}$$
$$\psi=\frac{1}{\sqrt{2}}[1s \alpha(1)1s \beta(2)-1s \alpha(2)1s \beta(1)]$$
$$\text{To normalize: } \int_{allspace} \psi^{*}\psi=1=\int\int\left[\frac{1}{\sqrt{2}}[1s \alpha^{*}(1)1s \beta^{*}(2)-1s \alpha^{*}(2)1s \beta^{*}(1)]\right]\left[\frac{1}{\sqrt{2}}[1s \alpha(1)1s \beta(2)-1s \alpha(2)1s \beta(1)]\right] d\tau_{1}d\tau_{2}$$
$$=\frac{1}{2}\int\int[1s \alpha^{*}(1)1s \beta^{*}(2)\times1s \alpha(1)1s \beta(2)]d\tau_{1}d\tau_{2}-\frac{1}{2}\int\int[1s \alpha^{*}(1)1s \beta^{*}(2)\times1s \alpha(2)1s \beta(1)]d\tau_{1}d\tau_{2}$$
$$-\frac{1}{2}\int\int[1s \alpha^{*}(2)1s \beta^{*}(1)\times1s \alpha(1)1s \beta(2)]d\tau_{1}d\tau_{2}+\frac{1}{2}\int\int[1s \alpha^{*}(2)1s \alpha^{*}(2)\times1s \alpha(2)1s \beta(1)]d\tau_{1}d\tau_{2}=\frac{1}{2}(2)=1$$


**6.27: Show that the term symbols for an $\color{bred}np^4$ electron configuration are the same as for an $\color{bred}np^2$ electron configuration.**


$$\text{The general formula of a term symbol: }^{2S+1}L_{J}$$

$$\text{Observations: }\begin{align*}
&1. \text{ The number of unpaired electrons is 2 in both of them}\\
&2. \text{ There are 15 microstates in each one  of them}\\
&3. \text{ They will have the same S and L values }
\end{align*}$$
$$\therefore \text{They will have the same term symbol}$$


**8.34: Determine the electron configuration of a magnesium atom in its ground state, and its ground-state term symbol.**

$$Mg: 1s^{2}2s^{2}2p^{6}3s^{2}$$
$$\text{Microstates = }\prod_\text{subshells} \frac{g_{k}!}{N_{k}!(g_{k}-N_{k})!} =\frac{2!}{2!(0)!}\frac{2!}{2!(0)!}\frac{6!}{6!(0)!}\frac{2!}{2!(0)!}=1$$
$$S=\sum\limits_{i}m_{s_{i}}=\frac{1}{2}-\frac{1}{2}=0$$

$$L=\sum\limits_{i}m_{l_{i}}=0+0=0$$
$$J=|L+S|,|L+S|-1,|L+S|-2,\dots,|L-S| =0$$
$$\text{Term symbol: } ^{1}S_{0}$$
**8.40: The orbital designations s, p, d, and f come from an analysis of the spectrum of atomic sodium. The series of lines due to $ns \space ^{2}S \to 3p \space ^{2}P$  transitions is called the sharp (s) series; the series due to $np \space ^{2}P \to 3s \space ^{2}S$ transitions is called the principal (p) series; the series due to $nd \space ^{2}D \to 3 p \space ^{2}P$ transitions is called the diffuse (d) series; and the series due to $nf \space ^{2}F \to 3d \space ^{2}D$ transitions is called the fundamental (f) series. Identify each of these series in Figure 8.4, and tabulate the wavelengths of the first few lines in each series.**


![[Pasted image 20220712231206.png|400]]

$$\text{Sharp series: }\begin{align*}

&11404  \text{ Å}\\
&11382  \text{ Å}\\
& 6154.2 \text{ Å}\\
&6160.7  \text{ Å}\\
&5153.6  \text{ Å}\\
&5149.1  \text{ Å}
\end{align*}$$
$$\text{Principal series: }\begin{align*}
& 5895.9 \text{ Å}\\
&5889.9  \text{ Å}\\
&3302.3  \text{ Å}\\
&3302.9  \text{ Å}\\
& 2852.8 \text{ Å}\\
&2853.0  \text{ Å}\\
\end{align*}$$
$$\text{Diffuse series: }\begin{align*}
&8194.8  \text{ Å}\\
& 5682.7 \text{ Å}\\
&5688.2  \text{ Å}\\
& 4978.6 \text{ Å}\\
&4982.9  \text{ Å}\\
&8183.3  \text{ Å}\\

\end{align*}$$
$$\text{Fundamental series: }\begin{align*}
& 18459\text{ Å}\\
&12678  \text{ Å}\\

\end{align*}$$
