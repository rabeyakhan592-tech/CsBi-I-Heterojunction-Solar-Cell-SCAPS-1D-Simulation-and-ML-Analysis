# SCAPS-1D Simulation Results

This file summarizes the main SCAPS-1D simulation results reported in the published study. The study investigates the effects of absorber materials, layer thicknesses, doping densities, transport layers, back-contact work function, and operating temperature on the performance of a CsBi₃I₁₀-based heterojunction solar cell.

The main photovoltaic parameters considered are:

- Open-circuit voltage (Voc)
- Short-circuit current density (Jsc)
- Fill factor (FF)
- Power conversion efficiency (PCE)

The simulations were performed under AM 1.5G illumination at an intensity of 100 mW/cm². The initial device was evaluated at 300 K.

> **Note on digitized values:** Values marked with `~` were approximately extracted from the plotted curves or bars in the published figures because the original SCAPS-1D output files are not available. Values without `~` are numerical values explicitly reported in the paper. Digitized values should therefore be treated as approximate and may differ slightly from the original simulation output.

---

## 1. Initial Device

The initial heterojunction structure used in the study was:

`Au / MoO₃ / CZTS / CsBi₃I₁₀ / PCBM / ITO`

The initial device achieved a PCE of **13.56%** under AM 1.5G illumination.

The SCAPS-1D simulation was performed at **300 K** with an illumination intensity of **100 mW/cm²**.

---

## 2. Semiconductor Layer Selection

Four semiconductor materials were investigated as the bottom absorber layer:

- CZTS
- CZTGS
- Al₀.₈Ga₀.₂Sb
- GaAs

GaAs was selected because it provided the best overall combination of Jsc, FF, and PCE.

| Semiconductor | Voc (V) | Jsc (mA/cm²) | FF (%) | PCE (%) |
|---|---:|---:|---:|---:|
| CZTS | 1.24 | ~13.50 | ~81.50 | 13.56 |
| CZTGS | ~1.19 | ~18.20 | ~76.00 | ~16.50 |
| Al₀.₈Ga₀.₂Sb | ~0.98 | ~23.50 | ~61.00 | ~14.00 |
| GaAs | ~1.04 | 23.86 | 82.33 | 20.44 |

CZTS produced the highest reported Voc of **1.24 V**, whereas GaAs produced the highest Jsc, FF, and PCE, with **23.86 mA/cm²**, **82.33%**, and **20.44%**, respectively.

The values marked with `~` were obtained by reading the corresponding plotted results in Fig. 3.

---

## 3. GaAs Thickness Optimization

The thickness of the GaAs semiconductor layer was varied from **0.2 to 0.8 μm**.

The simulation showed that Jsc, FF, and PCE generally increased with increasing GaAs thickness, while Voc showed a slight decrease.

| GaAs thickness (μm) | Voc (V) | Jsc (mA/cm²) | FF (%) | PCE (%) |
|---:|---:|---:|---:|---:|
| 0.2 | ~1.055 | ~20.73 | 81.84 | ~17.80 |
| 0.4 | ~1.040 | ~24.06 | 82.32 | ~20.60 |
| 0.6 | ~1.031 | ~25.17 | ~82.48 | ~21.40 |
| 0.8 | ~1.024 | ~25.91 | 82.55 | ~21.90 |

The FF increased from approximately **81.8% to 82.5%** as the GaAs thickness increased.

The study selected **0.8 μm** as the optimized GaAs thickness.

The numerical values marked with `~` were extracted from Fig. 6.

---

## 4. GaAs Doping Density Optimization

The GaAs acceptor density was varied from:

`1 × 10¹⁵ to 1 × 10¹⁸ cm⁻³`

Voc increased from approximately **1.02 to 1.03 V** across the investigated range.

The best performance was obtained at:

`5 × 10¹⁶ cm⁻³`

| GaAs acceptor density (cm⁻³) | Voc (V) | Jsc (mA/cm²) | FF (%) | PCE (%) |
|---:|---:|---:|---:|---:|
| 1 × 10¹⁵ | ~1.020 | ~26.08 | ~81.90 | ~21.85 |
| 1 × 10¹⁶ | ~1.028 | ~26.21 | ~82.55 | ~22.20 |
| 5 × 10¹⁶ | ~1.029 | ~26.24 | ~82.80 | ~22.31 |
| 1 × 10¹⁷ | ~1.030 | ~26.23 | ~82.78 | ~22.30 |
| 1 × 10¹⁸ | ~1.032 | ~25.76 | ~81.45 | ~21.62 |

The study identified **5 × 10¹⁶ cm⁻³** as the optimum GaAs acceptor density.

The paper text reports a PCE of **23.4%** at this optimum condition, while the graph-digitized value is approximately **22.31%**. The reported value from the paper should be used when citing the published result.

The values marked with `~` were extracted from Fig. 8.

---

## 5. Hole Transport Layer (HTL) Selection

Four HTL materials were compared:

- MoO₃
- Cu₂O
- CuI
- NiO

The photovoltaic parameters were relatively similar for the different HTLs, while NiO provided the highest reported PCE.

| HTL | Voc (V) | Jsc (mA/cm²) | FF (%) | PCE (%) |
|---|---:|---:|---:|---:|
| MoO₃ | ~1.031 | ~26.00 | ~82.80 | ~22.20 |
| Cu₂O | ~1.024 | ~26.00 | ~84.50 | ~22.50 |
| CuI | ~1.034 | ~26.00 | ~81.50 | ~21.90 |
| NiO | ~1.036 | ~26.00 | ~85.00 | 22.89 |

NiO was selected as the HTL because it provided the highest reported PCE of **22.89%**.

The values marked with `~` were extracted from Fig. 9.

---

## 6. Electron Transport Layer (ETL) Selection

Four ETL materials were investigated:

- PCBM
- CeOₓ
- ZnSe
- WS₂

ZnSe provided the best overall performance among the investigated ETLs.

| ETL | Voc (V) | Jsc (mA/cm²) | FF (%) | PCE (%) |
|---|---:|---:|---:|---:|
| PCBM | ~1.041 | ~26.00 | ~85.00 | ~23.00 |
| CeOₓ | ~1.023 | ~30.10 | ~87.00 | ~26.80 |
| ZnSe | ~1.031 | 30.16 | ~87.00 | 27.05 |
| WS₂ | ~1.026 | ~29.80 | ~86.00 | ~26.30 |

ZnSe was selected as the ETL because it provided the highest reported Jsc and PCE.

The reported Jsc for ZnSe was **30.16 mA/cm²**, while its PCE was **27.05%**.

The values marked with `~` were extracted from Fig. 10.

---

## 7. ZnSe Thickness Optimization

The ZnSe ETL thickness was investigated at:

`0.01, 0.05, 0.08, 0.10, and 0.30 μm`

The open-circuit voltage showed little variation across the investigated thicknesses.

The first four thicknesses, from **0.01 to 0.10 μm**, produced approximately similar Jsc values. At **0.30 μm**, Jsc decreased to **30.14 mA/cm²**.

| ZnSe thickness (μm) | Voc (V) | Jsc (mA/cm²) | FF (%) | PCE (%) |
|---:|---:|---:|---:|---:|
| 0.01 | ~1.029 | ~30.17 | ~87.08 | 27.10 |
| 0.05 | ~1.030 | ~30.165 | ~86.95 | ~27.06 |
| 0.08 | ~1.030 | ~30.162 | ~86.92 | ~27.05 |
| 0.10 | ~1.030 | ~30.161 | ~86.91 | ~27.05 |
| 0.30 | ~1.030 | 30.14 | ~86.83 | ~27.01 |

The optimum ZnSe thickness was **0.01 μm**, producing a reported PCE of **27.10%**.

The values marked with `~` were extracted from Fig. 11.

---

## 8. ZnSe Doping Density Optimization

The ZnSe donor density was investigated over:

`1 × 10¹⁵ to 1 × 10²⁰ cm⁻³`

Voc remained approximately **1.03 V** throughout the investigated range.

Jsc remained close to **30.17 mA/cm²**, except at `1 × 10²⁰ cm⁻³`, where it decreased to **30.10 mA/cm²**.

| ZnSe donor density (cm⁻³) | Voc (V) | Jsc (mA/cm²) | FF (%) | PCE (%) |
|---:|---:|---:|---:|---:|
| 1 × 10¹⁵ | ~1.030 | ~30.17 | ~87.18 | 27.12 |
| 1 × 10¹⁶ | ~1.030 | ~30.17 | ~87.12 | ~27.11 |
| 5 × 10¹⁷ | ~1.030 | ~30.17 | ~87.10 | 27.12 |
| 1 × 10¹⁸ | ~1.030 | ~30.16 | ~87.08 | ~27.10 |
| 1 × 10²⁰ | ~1.030 | 30.10 | ~87.05 | ~27.04 |

The optimum ZnSe donor density was selected as:

`5 × 10¹⁷ cm⁻³`

At this condition, the paper reports:

- Voc: approximately **1.03 V**
- Jsc: approximately **30.17 mA/cm²**
- FF: **87.2%**
- PCE: **27.12%**

The values marked with `~` were extracted from Fig. 12.

---

## 9. CsBi₃I₁₀ Thickness and Doping Density Optimization

The CsBi₃I₁₀ absorber layer was optimized by varying its thickness and shallow acceptor density.

The best combination was:

- Thickness: **0.2 μm**
- Shallow acceptor density: **1 × 10¹⁴ cm⁻³**

At this condition, the optimized device achieved:

| Parameter | Value |
|---|---:|
| CsBi₃I₁₀ thickness | 0.2 μm |
| Acceptor density | 1 × 10¹⁴ cm⁻³ |
| Voc | 1.03 V |
| Jsc | 30.2 mA/cm² |
| FF | 88.1% |
| PCE | 27.40% |

The study also reports the following results from the two-dimensional optimization:

- Maximum Voc: **1.32 V** at a CsBi₃I₁₀ thickness of **1.0 μm** and an acceptor density of **1 × 10¹⁸ cm⁻³**.
- Maximum Jsc: **30.2 mA/cm²** at **0.2 μm** thickness and **1 × 10¹⁴ cm⁻³** acceptor density.
- Maximum FF: **88.1%** at **0.2 μm** thickness and **1 × 10¹⁴ cm⁻³** acceptor density.
- PCE at **1.0 μm** thickness and **1 × 10¹⁸ cm⁻³** acceptor density: approximately **5.7%**.

Figures 13 and 14 present these results as two-dimensional contour plots. Because the original numerical grid is not available, the contour plots are not converted into a complete numerical dataset.

---

## 10. Back Contact Work Function and Temperature

The effect of the back-contact work function and operating temperature was investigated using the optimized device configuration.

The highest PCE region occurred at an operating temperature of **275 K** with a work function between **4.8 and 5.8 eV**.

The study reports:

| Parameter | Result |
|---|---|
| Selected temperature | 275 K |
| Selected work function | 5.8 eV |
| Maximum Jsc region | 325 K, work function 4.8–5.8 eV |
| Maximum reported Voc | 1.071 V |
| Highest PCE region | 275 K, work function 4.8–5.8 eV |
| Highest FF region | 275 K, work function 4.8–5.8 eV |

Based on the combined analysis, the final selected back-contact work function was **5.8 eV** at **275 K**.

Figures 13 and 14 show the effects of these parameters graphically.

---

## 11. Final Optimized Device

After sequential optimization of the semiconductor layer, HTL, ETL, absorber layer, back-contact work function, and operating temperature, the final device architecture reported in the study was:

`Al / NiO / GaAs / CsBi₃I₁₀ / ZnSe / ITO`

The final simulated photovoltaic performance was:

| Parameter | Final value |
|---|---:|
| Voc | 1.03 V |
| Jsc | 30.2 mA/cm² |
| FF | 88.1% |
| PCE | 27.40% |

The final optimized device therefore achieved a simulated PCE of **27.40%**, compared with **13.56%** for the initial device.

---

## Summary of Optimized Parameters

| Device parameter | Optimized value |
|---|---:|
| Semiconductor | GaAs |
| GaAs thickness | 0.8 μm |
| GaAs acceptor density | 5 × 10¹⁶ cm⁻³ |
| HTL | NiO |
| ETL | ZnSe |
| ZnSe thickness | 0.01 μm |
| ZnSe donor density | 5 × 10¹⁷ cm⁻³ |
| CsBi₃I₁₀ thickness | 0.2 μm |
| CsBi₃I₁₀ acceptor density | 1 × 10¹⁴ cm⁻³ |
| Back-contact work function | 5.8 eV |
| Selected temperature | 275 K |
| Final Voc | 1.03 V |
| Final Jsc | 30.2 mA/cm² |
| Final FF | 88.1% |
| Final PCE | 27.40% |

---

