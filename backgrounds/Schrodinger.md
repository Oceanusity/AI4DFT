# Tradtional Physics
keywords: **particle**, **wave**, **wavefunction**, **matter wave**.

For the classic physics, object is treated as particle. It exists in a centain position $x$ with momentum $p = mv$.

Conceptually, wave is combined with magitude and phase denoting as $Ae^{i\theta}$, where $A$ is the mangitude and $\theta$ is the phase.
With the periodical property of wave, the phase is changed cyclicaly with the time showing as $\theta = \omega t$, where $\omega$ is the angular frequency.

<!-- ![phase_with_time](https://github.com/Oceanusity/AI4DFT/assets/36795878/1654f8ef-c1cb-4a54-9ef6-b15cae5e1377) -->
<p align="center">
<img src="https://github.com/Oceanusity/AI4DFT/assets/36795878/1654f8ef-c1cb-4a54-9ef6-b15cae5e1377" width="400" class="center" alt="phase_with_time"/>
</p>

As shown in the figure imported from [Wiki](https://commons.wikimedia.org/wiki/File:Out_of_phase_AE.gif), the phase $\theta$ changes periodically with time $t$ with a fix frequency $f$. 

As waves propagate through space, the phase varies with distance from the sound source with $\Delta \theta = \frac{2 \pi \bar{r}}{\lambda} = \mathbf{k} \mathbf{r}$, where $\mathbf{r}$ is the position vector from the sound source, $\lambda$ is the wavelength and $\mathbf{k} = \frac{2 \pi}{\lambda} \frac{\mathbf{r}}{\bar{r}}$ is the wavevector.

In conclusion, the waves can be denoted as $f(\mathbf{r}, t) = Ae^{i(\mathbf{k}\mathbf{r} - \omega t)}$ to consider the space and time dimension.

Then, it is observed that light has wave–particle duality. That's to say, light can also be denoted as $f(\mathbf{r}, t) = Ae^{i(\mathbf{k}\mathbf{r} - \omega t)}$, which is one kind of electromagnetic waves.

Furthermore, with the concept of matter waves proposed by DeBroglie, particles can also be represented as waves with wavelength $\lambda = \frac{h}{p}$, where $h$ is the Planck constant, and $p$ is the momentum. 
For the situation of standing wave which is time-independent, when the momentum of a particle is determined, the corresponding wavelength is established, enabling the representation wavefunction.

# Time-independent Schrödinger Equation
keywords: **momentum**, **operator**.

When consider the electronic wavefunctions $\Psi(r_1, r_2, \cdots, r_n)$, it describes the states of all coupled electronics in this system. 
For the stable and static system, the total energy of electronics is composed of coulumb potential and kinetic energy.
For the kinetic energy, $K = \frac{1}{2} m_e v^2 = \frac{p^2}{2m_e}$. 
With matter waves proposed by DeBroglie $\lambda = \frac{h}{p}$, then $K = \frac{h^2}{2m_e \lambda^2}$ and $\nabla^2 f(\mathbf{r}, t) = \frac{(2\pi)^2}{\lambda^2} f(\mathbf{r}, t)$. 
Then, 
$$\hat{K}  \Psi(r_1, r_2, \cdots, r_n) = \frac{p^2}{2m_e}  \Psi(r_1, r_2, \cdots, r_n) = \frac{h^2}{2m_e \lambda^2}  \Psi(r_1, r_2, \cdots, r_n) = \frac{\hbar^2}{2 m_e} \nabla^2 \Psi(r_1, r_2, \cdots, r_n).$$

For the coulumb potential, $V = - \sum_{i,j} \frac{ke_i e_j}{r_{ij}}$. 
Therefore, the time-independent schrödinger equation is shown as $$(\frac{\hbar^2}{2 m_e} \nabla^2 + V ) \Psi = E \Psi.$$
Here, $\hat{H}= (\frac{\hbar^2}{2 m_e} \nabla^2 + V)$ is the Hamiltonian operator and the $\Psi$ is the corresponding eigen wavefunction. Note that operator takes function as input and maps it into another function.

# Reference
[LibreTextsChemistry: Basic Quantum Mechanical Models ](https://chem.libretexts.org/Bookshelves/Physical_and_Theoretical_Chemistry_Textbook_Maps/Time_Dependent_Quantum_Mechanics_and_Spectroscopy_(Tokmakoff)/01%3A_Overview_of_Time-Independent_Quantum_Mechanics/1.03%3A_Basic_Quantum_Mechanical_Models)
