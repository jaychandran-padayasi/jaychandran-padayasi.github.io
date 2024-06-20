---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
redirect_from:
  - /portfolio
---

{% include base_path %}

I am a dissertation-year PhD candidate and Presidential Fellow at the Ohio State University. The unifying theme of my research has been to exploit the power of conformal symmetry in explaining critical phenomena in quantum systems. Specifically, I have utilized the tools of numerical and analytical conformal bootstrap to explore the space of quantum critical phenomena and conformal field theories (CFTs) that describe them. I am broadly interested in criticality across nature, and the predictive power of symmetries in studying it.


O(N) vector models with a boundary
======
<img align="left" src="../images/ONphasediagram.png" alt="O(N) Boundary phases" width="500"/> In an ongoing project with my collaborators including Max Metlitski (MIT) and Marco Meineri (University of Turin), I have been studying the boundary criticality in O(N) vector models in 3d. O(N)-vector models, especially the Ising (O(1)), the x-y (O(2)) and the Heisenberg (O(3)) have been canonically used to describe and study phase transitions in a diverse class of systems, including quantum magnets, superfluids and superconductors. Using conformal invariance, we rigorously checked and proved the existence of an earlier-predicted extraordinary-log phase in the O(3) and O(4) models [[1]](https://www.scipost.org/SciPostPhys.12.6.190). In this phase, the system is critical in the bulk but the correlations of the order parameter on the boundary decay logarithmically slowly (the boundary is almost, but not quite ordered): 

$$\langle \vec{S}(\vec{x})\vec{S}(\vec{y})\rangle \sim \frac{1}{(\mathrm{log}|\vec{x} - \vec{y}|)^{q(N)}}.$$  

Our main finding was that the O(3) (Heisenberg) model, that describes many real-world magnets, exhibits this phase, which makes it relevant to experiments and numerics. We argued that if the surface coupling is sufficiently enhanced, either due to natural reasons or artificially enforced by depositing another magnetic material with higher Tc, it would be possible to observe the sharp onset of surface magnetization below the bulk Tc. Since our work was published, the logarithmic decay has been directly observed in Monte Carlo simulations of the O(N) vector models [[2]](https://iopscience.iop.org/article/10.1088/1742-6596/2207/1/012003), and it has been noted that it could be observed at the quantum critical point of the 2+1-dimensional O(N) model under decoherence/weak measurement [[3]](https://journals.aps.org/prxquantum/abstract/10.1103/PRXQuantum.4.030317). 

Conformal invariance in multifractals
======
<img align="left" src="../images/WF111-Anderson_transition-multifractal.jpeg" alt="Multifractal Wavefunction" width="500"/> Anderson localization is a well-researched phenomenon which describes metal to insulator transitions in the presence of disorder. In many non-interacting systems with disorder, there exists a mobility edge (a specific energy below which all the states are localized). At this mobility edge, the wavefunctions are multifractal measures. In [[4]](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.131.266401), we studied multifractal (MF) correlators from a CFT perspective. Multifractals are mathematical constructs that extend the concept of fractals by characterizing the varying degree of self-similarity and complexity across different scales. The scaling behavior of multifractals is described by a continuous infinity of scaling exponents called the MF spectrum $\Delta_q$. We showed that if a MF measure can be described by a conformally-invariant critical field theory, then in arbitrary dimensions $d \ge 2$, the MF spectrum must be parabolic, i.e. $ \Delta_q = b q(q_* - q). $ In the context of Anderson transitions, our exact result contradicts several numerical and perturbative data. This lead us to conclude that Anderson transitions represent unusual critical points  where scale invariance may not be enhanced to conformal invariance.