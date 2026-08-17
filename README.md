# CsBi₃I₁₀ Heterojunction Solar Cell | SCAPS-1D Simulation and ML Analysis

This repository contains the computational datasets, simulation files, and machine learning code associated with the published research on lead-free **CsBi₃I₁₀-based heterojunction perovskite solar cells**. 

The study leverages SCAPS-1D for physical device modeling and combines it with Random Forest Regression and SHAP (SHapley Additive exPlanations) to systematically evaluate and optimize solar cell performance parameters.

---

## Optimized Device Architecture

The final optimized multi-layer device configuration proposed in this study is structured as follows:

```text
Al (Back Contact) / NiO (HTL) / GaAs (Semiconductor) / CsBi₃I₁₀ (Absorber) / ZnSe (ETL) / ITO (Front Contact)
```

Through rigorous computational tuning, this specific architecture achieved a **simulated power conversion efficiency (PCE) of 27.40%**.

### Device Parameter Specifications
The table below highlights the specific physical parameters determined during the final optimization phase:

| Component / Parameter | Material / Layer | Optimized Value |
| :--- | :--- | :--- |
| **Semiconductor Layer** | GaAs | Included |
| **HTL (Hole Transport Layer)** | NiO | Included |
| **Perovskite Absorber** | CsBi₃I₁₀ | Thickness: 0.2 μm <br> Acceptor Density (N<sub>A</sub>): 1 × 10¹⁴ cm⁻³ |
| **ETL (Electron Transport Layer)** | ZnSe | Thickness: 0.01 μm <br> Donor Density (N<sub>D</sub>): 5 × 10¹⁷ cm⁻³ |
| **Back Contact Work Function** | Al | 5.8 eV |
| **Operating Temperature** | — | 275 K |

---

## Repository Structure

```text
CsBi3I10-Heterojunction-Solar-Cell/
│
├── README.md               # Project documentation
│
├── scaps/
│   ├── input-parameters/   # Input device configuration properties (.aps files/values)
│   └── simulation-results/ # Raw or compiled numerical text exports from SCAPS
│
├── data/
│   └── ml-dataset.csv      # Compiled dataset containing the 200 data points
│
├── machine-learning/
│   ├── random-forest/      # Python scripts/notebooks for regression training
│   └── shap-analysis/      # Global and local feature importance evaluation scripts
│
└── figures/                # Selected graphical visualizations and plots
```

---

## Machine Learning Workflow

A **Random Forest Regression** framework was implemented to map out the non-linear relationship between structural variations and the target PV metrics:

* **Dataset:** 200 simulation data points mapping physical variations to final efficiencies.
* **Features Considered:** Perovskite layer thickness, doping density, and defect density.
* **Target Output:** Power Conversion Efficiency (PCE).
* **Data Split:** 80% Training data, 20% Testing data.
* **Explainable AI:** SHAP analysis was deployed post-training to isolate exactly how individual input variables drive or drag down the final model predictions.

---

## Publication & Citation

If you use the data, scripts, or configuration parameters hosted in this repository for your academic work, please cite our peer-reviewed journal article:

### Standard Reference
> Khan, R., Farjana, N., Jim, M. J. A., Al-Humaidi, J. Y., Islam, M. R., & Rana, M. M. (2025). **Numerical simulation and performance enhancement of CsBi₃I₁₀-based heterojunction solar cell with various semiconductor layers (CZTS, CZTGS, Al₀.₈Ga₀.₂Sb, GaAs) along with machine learning-based analysis.** *Solar Energy*, 295, 113539.
> 
> **DOI:** [10.1016/j.solener.2025.113539](https://doi.org)

### BibTeX Format
```bibtex
@article{Khan2025CsBi3I10,
  title   = {Numerical simulation and performance enhancement of CsBi3I10-based heterojunction solar cell with various semiconductor layers (CZTS, CZTGS, Al0.8Ga0.2Sb, GaAs) along with machine learning-based analysis},
  author  = {Khan, Rabeya and Farjana, Nadira and Jim, Mst. Jahida Akter and Al-Humaidi, Jehan Y. and Islam, Md Rasidul and Rana, Md Masud},
  journal = {Solar Energy},
  volume  = {295},
  pages   = {113539},
  year    = {2025},
  doi     = {10.1016/j.solener.2025.113539}
}
```

---

## Notes

This repository is strictly intended to support scientific open-source reproducibility. The full-text published journal article is protected under publisher copyright and is **not** distributed within this repository. Only shareable computational inputs, simulation data logs, python analytics code, and descriptive assets are included.


---

## Notes

This repository is strictly intended to support scientific open-source reproducibility. The full-text published journal article is protected under publisher copyright and is **not** distributed within this repository. Only shareable computational inputs, simulation data logs, Python analytics code, and descriptive assets are included.
