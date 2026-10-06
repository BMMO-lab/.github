# bmmo-lab

> **BMMO** (/ˈbiːmoʊ/, pronounced *“bimmo”* — the **B** already says “bee”)  
> **B**inary **M**icromixer **M**odeling & **O**ptimization.

Welcome to the open-source initiative dedicated to bridging **SciML**, **microfluidics**, and **nanomedicine manufacturing**.

---

### Mission

Designing microreactors for therapeutic lipid nanoparticle (LNP) assembly and RNA formulation currently relies on
either intuition, trial-and-error chip microfabrication, or computationally prohibitive 3D CFD-PBM simulations requiring days on HPC clusters. 

**BMMO** develops operator learning surrogates that compress full 3D fluid dynamics and convective-diffusive transport
from **days of compute into milliseconds**, enabling real-time mixer design, automated inverse geometry optimization, and controllable nanoparticle synthesis.

---

### Ecosystem

| Repository | Status | Focus |
| :--- | :--- | :--- |
| [`bmmo-core`](https://github.com/bmmo-lab/bmmo-core) | Active Dev | Neural operators, surrogate PDE solvers, mass conservation layers |

---

### Research & Citation

If you use BMMO modules or architectures in academic research, please cite our corresponding publications and software releases.
```bibtex
@software{bmmo_core,
  author = {BMMO Lab Contributors},
  title  = {BMMO: Binary Micromixer Modeling Optimization},
  url    = {https://github.com/bmmo-lab/bmmo-core},
  year   = {2026}
}

---

<p align="center">
  <sub>Maintained by the <b>BMMO Lab</b> research initiative. Released under the Apache 2.0 License.</sub>
</p>
