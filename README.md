# Bryan Lukehart-Yun

**M.S. Mechanical Engineering, Rochester Institute of Technology (2025)**  
_Dynamic Systems, Nonlinear SysID, State Estimation & Soft Robotics Actuators_  
[Email](mailto:bryan.lukehartyun@gmail.com) | [Publications](#publications)

---

I build experimental testbeds, open datasets, and estimation/control research for hysteretic and nonlinear physical systems. My work started with high-rate empirical system identification, integration of Machine-Learning principles related to Modeling, and physical soft robotics characterization.

I had previously conducted research at **Naval Research Laboratory** (hexapod C++ kinematic constraints), **Army Research Laboratory** (piezoelectric MEMS batch V&V) as a ORAU Journeyman Fellow, and a REU stint at **Harvard University** (*Whitesides Research Group*, kirigami actuators). 

> [!IMPORTANT]
> Currently preparing doctoral applications related to robotics.

### Core Technical Focus

- **Nonlinear SysID & Hysteresis Modeling:** Characterized soft actuator dynamics across 24 operating regimes, characterizing open-loop performance.
- **State Estimation & Control:** Demonstration UKF and NMPC pipelines to overcome Jacobian-spike singularities inherent to EKF on non-differentiable soft actuators.
- **Open Science & Data Infrastructure:** Engineered a 50M+ sample high-rate time-series testing pipeline (100/200 Hz), released on Zenodo, and V&V on hardware CAD test rigs in collaboration with RIT's Bioinspired Systems Engineering Lab (BioSEL) where I did my M.S research. 

---

## Featured Work

### [Time-Series Characterization Data for McKibben-Style Pneumatic Muscles](https://doi.org/10.5281/zenodo.23066619)

This Zenodo release is where the dataset related to pneumatic actuators relevant for soft robotics is located. For any questions related to paper or release, see below repo or email the authors.

### [BioSEL-FORGE](https://github.com/RIT-Biosel-Lab/BioSEL-FORGE)

The catch all repo related to research for BioSEL and McKibben Muscles. Also the place to create git issues and take a look at sample figures as needed.

### [BioSEL-PULSE](https://github.com/RIT-Biosel-Lab/BioSEL-PULSE)


Based on what was submitted to Zenodo originally, some extensions were done to add AGENTS.md and CLAUDE.md which has been disclosed as needed. Further work may be extended and uploaded / staged here before heading to Zenodo for future versions.

Features an open-source Python processing stack (10–12× speedup over legacy MATLAB done during thesis) supporting 11 interchangeable filtering methods via YAML configs and multi-core batch execution.

### [Empirical-Modeling-and-Data-Driven-Control-for-Nonlinear-Soft-Actuators](https://github.com/BryanLukehartYun/Empirical-Modeling-and-Data-Driven-Control-of-Nonlinear-Soft-Actuators)

Framework combining nonlinear SysID (NLARX), derivative-free state estimation (UKF), and NMPC trajectory tracking for pneumatic artificial muscles. Treated as a demonstration and **legacy left alone for references**.

### [Applied-Dynamics-and-Controls](https://github.com/BryanLukehartYun/Applied-dynamics-and-controls)

Dynamics, estimation, and mission design testbeds: 6-DOF nonlinear flight models, quaternion UKF attitude estimation under randomized disturbance noise, and interplanetary trajectory optimization with symbolic $\Delta V$ derivations.

> Problems solving for textbooks questions to stay sharp with aerospace and classical controls problems. -

## Publications & Preprints

- **Lukehart-Yun, B.** et al., _"A Large-Scale Time-Series Dataset for McKibben-Style Pneumatic Artificial Muscles and Soft Robotics Research,"_ Data in Brief, 2026. _Under review._. Dataset available on Zenodo @ *doi:10.5281/zenodo.23066619* -- Downloads Count: 240
- **Lukehart-Yun, B.** and Lamkin-Kennard, K., _"Stable Open-Loop Modelling of McKibben Muscle with Tunable Slider,"_ _In preparation for IEEE Transactions on Robotics (T-RO)_, 2027.
- **Lukehart-Yun, B.** and Lamkin-Kennard, K., _"[Redacted Title on Soft Robotics]"_ _In preparation for IEEE Robotics and Automation Letters (RA-L)_, 2027.

---

## Environment & Tooling

- **Computing & Controls:** Python (`uv`, NumPy, SciPy, pandas, scikit-learn, PyWavelets), C++, MATLAB / Simulink, Jupyter
- **Lab & DAQ:** High-rate data acquisition, optical/load cell instrumentation, ASTM materials testing, FDM/SLA rapid prototyping
- **Homelab & Infrastructure:** Tailscale mesh network, self-hosted Forgejo Git server, Linux (CachyOS / Fedora), macOS
- **Tools:** Neovim / Neovide, orgmode, DOOM Emacs with **EVIL Mode**, VS Code - Jupyter extension (rarely), LaTeX 
