---
tags: 🧠️/📝️/👨‍🏫/📥️
publish: true
aliases: 
---
# CHEM4502 - HW2 -  Created:  [[2022-06-18]]


### Chapter 3

**3-1: Evalulate $g =\hat A f$ , where $\hat A$ and $f$ are given below:**
$\hat A$ | $f$
--|--
a) SQRT | $x^{4}$
b) $\frac{d^{3}}{dx^{3}}+x^{3}$ | $e^{-ax}$
c) $\int_{0}^{1}dx$ | $x^{3}-2x+3$
d) $\frac{\partial^{2}}{\partial x^{2}}+\frac{\partial^{2}}{\partial y^{2}}+\frac{\partial^{2}}{\partial z^{2}}$ | $x^{3}y^{2}z^{4}$

a) $$g=\hat Af=\sqrt{x^{4}} = \boxed{\pm x^{2}}$$
b) $$g=\hat Af=\left(\frac{d^{3}}{dx^{3}}+x^{3}\right)e^{-ax}=\boxed{-a^{3}e^{-ax}+x^{3}e^{-ax}}$$
c) $$g=\hat Af=\int_{0}^{1}x^{3}-2x+3  \space dx=\left[\frac{x^{4}}{4}-x^{2}+3x\right]_{0}^{1}=\left(\frac{1}{4}-1+3\right)=\boxed{\frac{9}{4}}$$
d)$$g=\hat Af=\left(\frac{\partial^{2}}{\partial x^{2}}+\frac{\partial^{2}}{\partial y^{2}}+\frac{\partial^{2}}{\partial z^{2}}\right)x^{3}y^{2}z^{4}=\frac{\partial^{2}}{\partial x^{2}}(x^{3}y^{2}z^{4})+\frac{\partial^{2}}{\partial y^{2}}(x^{3}y^{2}z^{4})+\frac{\partial^{2}}{\partial z^{2}}(x^{3}y^{2}z^{4})$$
$$\boxed{=6xy^{2}z^{4}+2x^{3}z^{4}+12x^{3}y^{2}z^{2}}$$
**3-3: In each case, show that f(x) is an eigenfunction of the operator given. Find the eigenvalue.**
$\hat A$ | $f(x)$ 
-- | --
a) $\frac{d^{2}}{dx^{2}}$ | $\cos\omega x$ 
b) $\frac{d}{dt}$ | $e^{i\omega t}$ 
c) $\frac{d^{2}}{dx^{2}}+2 \frac{d}{dx} +3$ | $e^{\alpha x }$
d) $\frac{\partial}{\partial y}$ | $x^{2}e^{6y}$ 

a) $$\hat Af=af=\frac{d^{2}}{dx^{2}}\cos\omega x=-\omega^{2}\cos(\omega x) \qquad \boxed{\textrm{The eigenvalue is } -\omega^{2} }$$
b) $$\hat Af=af=\frac{d}{dt}e^{i\omega t}=i\omega  e^{i\omega t} \qquad \boxed{\textrm{The eigenvalue is } i\omega}$$
c) $$\hat Af=af=\left(\frac{d^{2}}{dx^{2}}+2 \frac{d}{dx} +3\right)e^{\alpha x}=(\alpha^{2}+2\alpha+3)e^{\alpha x} \space $$
$$\boxed{\textrm{The eigenvalue is } \alpha^{2}+2\alpha+3}$$
d) $$\hat Af=af=\frac{\partial}{\partial y} x^{2}e^{6y}=6x^{2}e^{6y } \qquad \boxed{\textrm{The eigenvalue is } 6}$$
**3-17: Prove that the set of functions:**$$\color{bred}\psi_{n}(x)=\left(\frac{1}{2a}\right)^{\frac{1}{2}}e^{\frac{i\pi n x}{a}} \qquad n=0,\pm1,\pm2,\dots$$
**is orthonormal over the interval $\color{bred}-a \leq x \leq a$.** 

$$\textrm{A set of functions is orthonormal if: } $$
$$\delta_{mn}=1 \textrm{ if } m=n$$
$$\delta_{mn}=0 \textrm{ if } m\neq n$$
$$\textrm{If }m=n:\int_{-a}^{a}\psi^{*}_{m}\psi_{n}dx= \frac{1}{2a}\int_{-a}^{a}e^{\frac{-i\pi m x}{a}}e^{\frac{i\pi n x}{a}}dx=\frac{1}{2a}\int_{-a}^{a}dx=\frac{1}{2a}(a-(-a))=1$$
$$\textrm{If }m\neq n:\int_{-a}^{a}\psi^{*}_{m}\psi_{n}dx= \frac{1}{2a}\int_{-a}^{a}e^{\frac{-i\pi m x}{a}}e^{\frac{i\pi n x}{a}}dx$$
$$\textrm{Using Euler's Formula: } e^{\frac{{i\pi}x(n-m)}{a}}=\cos\left(\frac{x\pi(n-m)}{a}\right)+i\sin\left(\frac{x\pi(n-m)}{a}\right)$$
$$= \frac{1}{2a}\int_{-a}^{a}\cos\left(\frac{x\pi(n-m)}{a}\right)+i\sin\left(\frac{x\pi(n-m)}{a}\right)dx=\frac{1}{2a}(0)=0$$
$$\therefore \textrm{The set of functions is orthonormal.}$$


**3-20: Calculate $\color{bred}\left<x\right>$ and $\color{bred}\left<x^{2}\right>$ for the n=2 state of a particle in a one-dimensional box of length a. Show that:**$$\color{bred}\sigma_{x}= \frac{a}{4\pi}\left(\frac{4\pi^{2}}{3}-2\right)^{\frac{1}{2}}$$
$$\textrm{From table (4.1): Multiply by x for position}$$
$$\left<x\right>=\int_{0}^{a}x\psi(x)^{*}\psi(x)dx=\frac{2}{a}\int_{0}^{a}x\sin^{2} \frac{n \pi x}{a}dx=\frac{2}{a}\left(\frac{a^{2}}{4}\right)=\frac{a}{2}$$
$$\left<x^{2}\right>=\int_{0}^{a}x^{2}\psi(x)^{*}\psi(x)dx=\frac{2}{a}\int_{0}^{a}x^{2}\sin^{2} \frac{n \pi x}{a}dx=\frac{a^{2}}{3}-\frac{a^{2}}{2n^{2}\pi^2}$$
$$\sigma^{2}=\left<x^{2}\right>-\left<x\right>^{2}=\left(\frac{a^{2}}{3}-\frac{a^{2}}{2n^{2}\pi^{2}}\right)-\left(\frac{a^{2}}{4}\right)$$
$$=\frac{a^{2}}{12}-\frac{a^{2}}{2n^{2}\pi^{2}}=\left(\frac{a}{2n\pi}\right)^{2}\left(\frac{n^{2}\pi^{2} }{3}-2\right)
$$
$$\sigma_{x}\space at \space n=2:\boxed{\left(\frac{a}{4\pi}\right)\left(\frac{4\pi^{2} }{3}-2\right)^\frac{1}{2}}$$

**3-26: What are the degeneracies of the first four energy levels for a particle in a three-dimensional box with a=b=1.5c?**

$$\color{bred}E=\frac{h^{2}}{8m}\left(\frac{n_{x}^{2}}{1^{2}}+\frac{n_{y}^{2}}{1^{2}}+\frac{n_{z}^{2}}{1.5^{2}}\right)$$
Energy Level  | Degeneracy
-- | --
$E_{111}$ | 1
$E_{211}$ | 2
$E_{221}$ | 1
$E_{112}$ | 1

3-27: **Many proteins contain metal porphyrin molecules. The general structure of the porphyrin molecule is:**![[Pasted image 20220619151616.png]]
**This molecule is planar and so we can approximate the $\color{bred}\pi$ electrons as being confined inside a square. What are the energy levels and degeneracies of a particle in a square of side a? The porphyrin molecule has 26 $\color{bred}\pi$ electrons. If we approximate the length of the molecule by 1000 pm, then what is the predicted lowest energy absorption of the porphyrin molecule? (The experimental value is~ 17 000 $\color{bred}cm^{-1}$)**

$$\textrm{2-D PIB Energy Formula: } E=\frac{h^{2}}{8m}\left(\frac{n_{x}^{2}}{a^{2}}+\frac{n_{y}^{2}}{a^{2}}\right)$$
Energy Level | Degeneracy
-- | --
$E_{11}$ | 1
$E_{21}$ | 2
$E_{22}$ | 1
$E_{31}$ | 2
$E_{32}$ | 2
$E_{33}$ | 1
$E_{41}$ | 2
$E_{42}$ | 2
$E_{43}$ | 2
$E_{44}$ | 1
$$\textrm{Lowest energy absorption } E_{11} \space and \space E_{21}:$$
$$E_{11}=\frac{h^{2}}{8m}\left(\frac{1^{2}}{a^{2}}+\frac{1^{2}}{a^{2}}\right) \qquad E_{21}=\frac{h^{2}}{8m}\left(\frac{2^{2}}{a^{2}}+\frac{1^{2}}{a^{2}}\right)$$
$$\Delta E=\frac{h^{2}}{8ma^{2}}\left(3\right)=\frac{(6.626\times10^{-34})^{2}}{8(9.11\times10^{-31})(1\times10^{-9})^{2}}\left(3\right)=1.81\times10^{-19}J$$
$$\textrm{Convert change in energy to wavenumber: }$$
$$\boxed{E=hc\tilde v \to \tilde v= 9.11\times10^{3}cm^{-1}}$$
**CHECK LATER WITH PROF**

**4-1: Which of the following candidates for wave functions are Normalizable over the indicated intervals?**

a. $\color{bred}e^{\frac{-x^{2}}{2}} \space (-\infty,\infty)$ 
b. $\color{bred}e^{x} \space (0,\infty)$ 
c. $\color{bred}e^{i\theta}\space (0,2\pi)$
d. $\color{bred}\sinh x \space (0,\infty)$ 
e. $\color{bred}xe^{-x} \space (0,\infty)$
**Normalize those that can be normalized. Are the others suitable wavefunctions?**

a.
$$\int_{-\infty}^{\infty}\psi^{*}\psi dx=\int_{-\infty}^{\infty}e^{-x^{2}} dx=1.772 \qquad \boxed{\textrm{Normalizable}}$$
$$=A^{2}\int_{-\infty}^{\infty}\psi^{*}\psi dx=1=A^{2}\int_{-\infty}^{\infty}e^{-x^{2}} dx=1.772A^{2}\to \boxed{A=\left(\frac{1}{1.772}\right)^{\frac{1}{2}}}$$

b.
$$\int_{0}^{\infty}\psi^{*}\psi dx=\int_{0}^{\infty}e^{2x} dx=\infty \qquad \boxed{\textrm{Not normalizable}}$$
$$\boxed{\textrm{The function is not finite.}}$$
c.

$$\int_{0}^{2\pi}\psi^{*}\psi dx=\int_{0}^{2\pi}e^{-i\theta+i\theta} d\theta=2\pi \qquad \boxed{\textrm{Normalizable}}$$
$$=A^{2}\int_{0}^{2\pi}\psi^{*}\psi dx=1=A^{2}\int_{0}^{2\pi}1 dx=A^{2}2\pi\to \boxed{A=(\frac{1}{2\pi})^{\frac{1}{2}}}$$

d.

$$\int_{0}^{\infty}\psi^{*}\psi dx=\int_{0}^{\infty}\sinh^{2}(x) dx=\infty \qquad \boxed{\textrm{Not normalizable}}$$
$$\boxed{\textrm{The function is not finite.}}$$
e.

$$\int_{0}^{\infty}\psi^{*}\psi dx=\int_{0}^{\infty}x^{2}e^{-2x} dx=0.25 \qquad \boxed{\textrm{Normalizable}}$$
$$=A^{2}\int_{0}^{\infty}\psi^{*}\psi dx=1=A^{2}\int_{0}^{\infty}x^{2}e^{-2x} dx=0.25A^{2}\to \boxed{A=2}$$

**4-2: Which of the following wave functions are normalized over the indicated two-dimensional intervals?**

**a.** $$\color{bred}e^{-(\frac{x^{2}+y^{2}}{2})} \qquad \qquad \begin{align}
0 \leq x \leq \infty\\
0 \leq y \leq \infty
\end{align}$$
**b.** $$\color{bred}e^{-(\frac{x+y}{2})} \qquad \qquad \begin{align}
0 \leq x \leq \infty\\
0 \leq y \leq \infty
\end{align}$$
**c.** $$\color{bred}\left(\frac{4}{ab}\right)^{\frac{1}{2}}\sin \frac{\pi x}{a}\sin \frac{\pi y}{b} \qquad \qquad \begin{align}
0 \leq x \leq a\\
0 \leq y \leq b
\end{align}$$
**Normalize those that aren't.**

a. $$\int\psi^{*}\psi =\int_{0}^{\infty}e^{-x^{2}}dx\int_{0}^{\infty}e^{-y^{2}}dy=0.886^{2}=0.785 \qquad \boxed{\textrm{Noramlizable.}}$$
$$=0.785A^{2}=1 \to\boxed{ A=1.129}$$
b.$$\int\psi^{*}\psi =\int_{0}^{\infty}e^{-x}dx\int_{0}^{\infty}e^{-y}dy=1^{2}=1 \qquad \boxed{\textrm{Noramlized.}}$$
c.$$=\int\psi^{*}\psi=\left(\frac{4}{ab}\right)\int_{0}^{a}\sin^{2} \frac{\pi x}{a}dx\int_{0}^{b}\sin^{2} \frac{\pi y}{b}dy = \left(\frac{4}{ab}\right)\left(\frac{a}{2}\right)\left(\frac{b}{2}\right)=1$$
$$\boxed{\therefore\textrm{The function is normalized}}$$

**4-5: Determine whether the following functions are acceptable or not as state functions over the indicated intervals:**

**a.** $\color{bred}\frac{1}{x}(0,\infty)$ 
**b.** $\color{bred}e^{-2x} \sinh x(0,\infty)$
**c.** $\color{bred}e^{-x}\cos x(0,\infty)$
**d.** $\color{bred}e^{x}(-\infty,\infty)$

The wavefunction must be well-behaved (Normalized) over its allowed interval (Particle must be somewhere in the allowed space)
	* $\psi(\boldsymbol x),\psi^{'}(\boldsymbol x)$ must be single-valued
	* $\psi(\boldsymbol x),\psi^{'}(\boldsymbol x)$ must be continuous
	* $\psi(\boldsymbol x),\psi^{'}(\boldsymbol x)$ must be finite
	* $\psi(\boldsymbol x)$ must approach 0 as $\boldsymbol x \to \pm \infty$ 

a. $\textrm{Not acceptable. Does not fulfill all conditions}$
b. $\textrm{Acceptable.fulfills all conditions}$
c. $\textrm{Acceptable. Fulfills all conditions}$
d. $\textrm{Not acceptable. Does not fulfill all conditions}$

**4-14: Determine whether the following pairs of operators commute:**
$\hat A$ |$\hat B$
-- | --
a. $\frac{d}{dx}$ | $\frac{d^{2}}{dx^{2}}+2\frac{d}{dx}$ 
b. $x$ | $\frac{d}{dx}$
c. SQR | SQRT
d. $x^{2}\frac{d}{dx}$ | $\frac{d^{2}}{dx^{2}}$ 

$$\textrm{Operators commute if } \hat A\hat Bf=\hat B\hat Af$$
a. $$\hat A \hat Bf=\frac{d}{dx}\left(\frac{d^{2}f}{dx^{2}}+2\frac{df}{dx}\right)=\frac{d^{3}f}{dx^{3}}+2\frac{d^{2}f}{dx^{2}}$$
 $$\hat B \hat Af=\left(\frac{d^{2}}{dx^{2}}+2\frac{d}{dx}\right)\frac{df}{dx}=\frac{d^{3}f}{dx^{3}}+2\frac{d^{2}f}{dx^{2}}$$
 $$\boxed{\therefore \textrm{The operators commute}}$$
 b. $$\hat A \hat Bf= x\left(\frac{df}{dx}\right)$$
 $$\hat B \hat Af=\left(\frac{d}{dx}\right)xf=1+x \frac{df}{dx}$$
 $$\boxed{\therefore \textrm{The operators do not commute}}$$
 c. $$\hat A \hat Bf=(\sqrt f)^{2}=f$$
 $$\hat B \hat Af=\sqrt (f^{2}) =\pm f $$
 $$\boxed{\therefore \textrm{The operators do not commute.}}$$
 d. $$\hat A \hat Bf=\left(x^{2}\frac{d}{dx}\right)\frac{d^{2}f}{dx} =x^{2} \frac{d^{3}f}{dx^{3}}$$
 $$\hat B \hat Af=\frac{d^{2}}{dx^{2}}\left(x^{2}\frac{df}{dx}\right)=\frac{d}{dx}\left(2x \frac{df}{dx}+x^{2} \frac{d^{2}f}{dx^{2}}\right)$$
 $$=\left(2 \frac{df}{dx}+2x \frac{d^{2}f}{dx^{2}}\right)+\left(2x \frac{d^2f}{dx^{2}}+x^{2} \frac{d^{3}f}{dx^{3}}\right)=x^{2}\frac{d^{3}f}{dx^{3}}+4x\frac{d^{2}f}{dx^{2}}+2\frac{df}{dx}$$
 $$\boxed{\therefore\textrm{The operators do not commute}}$$
 