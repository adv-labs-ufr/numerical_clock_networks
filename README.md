# 🕰️ Numerical Lab — *What Is a Clock?*
**A Collaborative Research Project on the Foundations of Timekeeping**

---

## 🌍 About This Repository

This public repository documents the ongoing collaborative research lab *“What Is a Clock?”* —  
an open numerical exploration of how clocks can be simulated, compared, and understood as a networked system.

Developed under the supervision of **Ulrich Warring**, *Institute of Physics, University of Freiburg.*

> ⚠️ **Privacy Notice:**  
> This is a public educational repository. No personal data (e.g., private email addresses, phone numbers, or home addresses) should ever be committed or shared here.  
> All communication and coordination occur through the designated Mattermost channel (link to be added later by the instructor).

We, the current student team, will:
- **Investigate what defines a clock** — physically, numerically, and conceptually.  
- **Develop simulations and analysis tools** to benchmark clocks within a triangular or extended network.  
- **Document our findings** transparently for future teams in this repository.  
- **Exchange ideas** through the associated **Mattermost channel** `#numerical-lab-clocks` *(link to be added later).*

This repository will remain **public** and be **extended by subsequent student teams**.  
Our responsibility is to build a clear and well-documented foundation, with readable notebooks, version-controlled data, and concise reasoning.  
Each contribution should make it easier for the next group to continue the scientific inquiry.

---

## 🎯 General Aim

We will explore the question:

> **What does it mean for something to be a clock?**

and extend this to the deeper inquiry:

> **How can clocks of very different kinds — atomic, engineered, geological, and astronomical — be connected and benchmarked within one coherent framework?**

Our goal is not only to simulate but to *think like metrologists*:  
to reason about observables, uncertainties, correlations, and the limits of synchronization across different physical domains.

---

## 🧩 Research Plan — Setting Out the Goal

Before beginning numerical work, each team will draft a **short research plan (≈1 page)** defining its own investigative focus within the broad theme.

This plan should be stored under:

/notes/research_plan.md

### 🧠 Guiding Questions

1. **Defining a Clock**
   - What observable property (phase, frequency, rotation, signal) makes your chosen system measurable as a clock?
   - How does its *stability* differ from its *accuracy*?
   - Can a clock exist without being compared to another?

2. **Benchmarking and Comparison**
   - How can we compare clocks without an external reference?
   - What does a *triangular* comparison network achieve that pairwise comparisons do not?
   - How could this concept generalize to more complex networks?

3. **Extending the Scope**
   - How might atomic clocks, quartz oscillators, Earth’s rotation, or pulsars all fit into a common timekeeping model?
   - Which observables (frequency drift, phase noise, orbital period, etc.) unify these systems conceptually?

4. **Numerical Realization**
   - Which aspects of your chosen model can be simulated with realistic noise parameters?
   - What assumptions will you make about noise types (white, flicker, random-walk)?
   - How can you visualize the performance and correlations within your network?

5. **Interpretation and Broader Context**
   - What does “synchronization” mean when combining systems from quantum to cosmological scales?
   - How might such models inform the design of a *resilient global time network*?
   - What are the epistemic limits of measuring time itself?

End your plan with a **succinct research goal statement**, for example:
> *We will simulate and benchmark three clocks — one atomic, one mechanical, one astronomical — to test how phase correlations can reveal network consistency even without an absolute reference.*

---

## 🧮 Suggested Numerical Foundations

Recommended starting points for simulation and analysis:
- Simulate clock signals: phase φ(t), fractional frequency deviation y(t).  
- Noise models: white phase noise, flicker frequency noise, random-walk frequency noise.  
- Benchmarking: pairwise phase differences Δ_ij(t), triangular closure relations.  
- Stability measures: Allan deviation σ_y(τ), power spectral density.

Useful open-source tools:
- [`numpy`](https://numpy.org/)
- [`matplotlib`](https://matplotlib.org/)
- [`allantools`](https://pypi.org/project/allantools/)
- [`networkx`](https://networkx.org/)

---

## 💡 Open Research Directions

Teams are encouraged to explore beyond the three-clock triangle:
- Hierarchical networks of fast (atomic) and slow (astronomical) clocks.  
- Modeling Earth’s rotation or pulsars as oscillators in the same network.  
- Including gravitational redshift or environmental coupling.  
- Investigating redundancy and trust in time networks.

---

## 📦 Repository Structure

/notes/               → research plans, reflections, references
/notebooks/           → numerical implementations (simulation, analysis)
/figures/             → generated plots and schematic illustrations
/report/              → evolving research summary (draft + final version)
requirements.txt      → Python dependencies

Each notebook should include:
- A clear purpose statement.  
- Commented code and parameters.  
- Plots or tables visualizing results.  
- References to related discussions in Mattermost.

---

## 💬 Collaboration and Continuity

All coordination takes place in the **Mattermost channel**  
➡️ `#numerical-lab-clocks`  
*(link to be added by the instructor)*

We will use it to:
- Share intermediate results and figures.  
- Discuss methods and results.  
- Link specific commits for feedback and transparency.

Future teams will inherit this repository.  
Please maintain a clear commit history and documentation style.  
Each contribution becomes part of a growing, open scientific record on time and frequency.

---

## 📚 References

- **M. A. Lombardi**, *NIST Time and Frequency Services*, NIST SP 250-89.  
- **W. J. Riley**, *Handbook of Frequency Stability Analysis*, NIST SP 1065.  
- **D. W. Allan, N. Ashby, C. C. Hodge**, *The Science of Timekeeping*, HP Application Note 1289.  
- **Calonico et al.**, “Optical clock networks for geodesy,” *Rep. Prog. Phys.* 81, 2018.  
- **Petit & Tavella**, “Atomic Timekeeping from 1955 to the Present,” *Metrologia* 54, R1 (2017).  
- **Chou et al.**, “Optical Clocks and Relativity,” *Science* 329, 1630 (2010).

---

## 🧠 Broader Learning Goals

- Reflect critically on the concept of time and what constitutes a clock.  
- Learn to express phase, frequency, and stability mathematically.  
- Connect numerical models across scales — from quantum oscillators to pulsars.  
- Practice open, collaborative research documentation.  
- Contribute to a long-term educational repository on timekeeping and metrology.

---

**Institute of Physics · University of Freiburg**  
*Advanced Laboratory / Quantum Sensing Module*  
© 2025 Contributors to the “Numerical Clock Networks” Project
