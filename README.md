# Hi, I'm Pedro Rivas Vega 👋

[![M2 MVA ENS Paris-Saclay](https://img.shields.io/badge/Graduate%20Student-M2%20MVA%20ENS%20Paris--Saclay-blue.svg)](https://www.master-mva.com/)
[![B.S. Mathematics](https://img.shields.io/badge/B.S.-Mathematics%20Univ.%20Sevilla-red.svg)](https://matematicas.us.es/)
[![Seeking Research Internship](https://img.shields.io/badge/Seeking%20Internship-April%202027-brightgreen.svg)]()
[![Email](https://img.shields.io/badge/Contact-pedrorivasvega%40gmail.com-orange.svg)](mailto:pedrorivasvega@gmail.com)

I am an **M2 MVA (Mathématiques, Vision, Apprentissage)** student at **École Normale Supérieure Paris-Saclay** with a pure and applied **Mathematics background from Universidad de Sevilla**. 

I focus on **World Models, Non-Generative Self-Supervised Learning (JEPAs), and Embodied AI for Robotics**. I am actively seeking a **6-month Research Internship starting April 2027** in World Models, Latent Dynamics, and Embodied Manipulation (targeting research labs such as General Intuition, UMA, and AMI Labs).

---

## 🔬 Research Interests

- **Latent World Models & JEPAs:** Transitioning from error-prone pixel prediction (diffusion / autoregressive video) to non-generative, action-conditioned predictive architectures in representation space ($z_{t+1} = g_\phi(z_t, a_t)$).
- **Geometric & Statistical Anti-Collapse Regularization:** Information-theoretic decorrelation (Barlow Twins, VICReg) and non-parametric hypothesis testing against isotropic Gaussians using the **Cramér-Wold device** and **Epps-Pulley empirical characteristic functions (SIGReg)**.
- **Embodied AI & Robotics Kinematics:** Visuomotor policy learning, $\mathrm{SE}(3)$-equivariant latent representations, and rigid-body dynamics / differential inverse kinematics with **Pinocchio** and **MuJoCo**.
- **Intuitive Physics Benchmarks:** Violation-of-Expectation (VoE) evaluation of self-supervised video models on conservation of mass, object permanence, and temporal causality.

---

## 🌟 Featured Research & Codebases

### 📘 [Foundations of EBMs & Joint Embedding Architectures: From Collapse to World Models](https://github.com/rivas-vega/TFG_Beamer)
*Bachelor's Thesis in Mathematics (100+ pages monograph, 64-slide defense), Univ. de Sevilla*  
*Advised by Prof. Eduardo Sánchez Karhunen (Candidate for Matrícula de Honor)*
- Rigorous mathematical treatise on Energy-Based Models, Gibbs-Boltzmann distributions, and Siamese collapse equilibria.
- Proved covering number bounds $\mathcal{O}(e^d)$ for negative sampling contrastive losses on high-dimensional spheres $\mathbb{S}^{d-1}$.
- Comprehensive mathematical formulation of **VICReg**, **JEPA**, and **SIGReg** via the **Cramér-Wold theorem** and closed-form Epps-Pulley test statistics.

### ⚡ [V-JEPA 2 Physics Scorer & VoE Benchmark Adapter](https://github.com/rivas-vega/vjepa2-physics-scorer-poc)
*Reproducible Benchmark Adapter & Serverless GPU API for Video Joint Embedding Predictive Architectures*
- Implemented a self-contained Violation-of-Expectation (VoE) scoring engine based on sliding-window latent prediction error.
- Zero private dependencies, fully tested with unit tests and offline synthetic verification in < 2 seconds.
- Deployed on serverless A10G/A100 GPUs via **Modal** with FastAPI endpoints for end-to-end spatiotemporal embedding and surprise evaluation.

### 🤖 [Embodied Robotics & Kinematics Foundations](https://github.com/rivas-vega)
*M2 MVA Robotics & Manipulation Coursework & Research Projects*
- Lie group geometry ($\mathrm{SE}(3)$, $\mathfrak{se}(3)$ exponential map, adjoint representations).
- Analytical kinematics and differential inverse kinematics using **Pinocchio** and **CasADi**.
- Trajectory optimization and closed-loop impedance control in simulated robotic manipulation environments (MuJoCo).

---

## 🧮 Technical Skills & Toolkit

- **Mathematical Foundations:** Measure Theory, High-Dimensional Probability, Spectral Graph Theory, Differential Geometry, Lie Groups & Algebras $\mathrm{SE}(3)$, Functional Analysis.
- **ML & World Models:** PyTorch, Self-Supervised Learning (I-JEPA, V-JEPA, DINO, VICReg), Transformers, Diffusion Models.
- **Robotics & Simulation:** Pinocchio, MuJoCo, ManiSkill, CasADi, Robot Operating Systems.
- **Engineering & Systems:** Linux/Bash, Modal (serverless GPU orchestration), FastAPI, Git, Docker, Slurm.

---

## 📬 Contact & Links

- **Email:** [pedrorivasvega@gmail.com](mailto:pedrorivasvega@gmail.com)
- **GitHub:** [@rivas-vega](https://github.com/rivas-vega)
- **Location:** Paris, France / Seville, Spain
- **Availability:** 6-Month Research Internship (April 2027 – September 2027)
