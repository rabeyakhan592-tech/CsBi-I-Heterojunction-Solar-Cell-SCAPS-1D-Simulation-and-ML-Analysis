# SCAPS-1D Simulation Results

This file summarizes the main SCAPS-1D simulation results reported in the published study. The values are extracted from the tables, figures, and discussion in the paper.

The main photovoltaic parameters considered are:

- Open-circuit voltage (Voc)
- Short-circuit current density (Jsc)
- Fill factor (FF)
- Power conversion efficiency (PCE)

## 1. Initial Device

The initial heterojunction structure used in the study was:

`Au / MoO₃ / CZTS / CsBi₃I₁₀ / PCBM / ITO`

The initial device achieved a PCE of **13.56%** under AM 1.5G illumination.

The SCAPS simulations were performed at **300 K** with an illumination intensity of **100 mW/cm²**.

---

## 2. Semiconductor Layer Selection

Four semiconductor materials were investigated as the bottom absorber layer:

- CZTS
- CZTGS
- Al₀.₈Ga₀.₂Sb
- GaAs

GaAs was selected as the preferred semiconductor because it provided the highest combination of Jsc, FF, and PCE.

| Semiconductor | Voc (V) | Jsc (mA/cm²) | FF (%) | PCE (%) |
|---|---:|---:|---:|---:|
| CZTS | 1.24* | — | — | — |
| CZTGS | — | — | — | — |
| Al₀.₈Ga₀.₂Sb | — | — | — | — |
| GaAs | — | 23.86 | 82.33 | 20.44 |

*CZTS produced the highest reported Voc of 1.24 V.

The paper does not provide all numerical values from this comparison in the text; the remaining values are presented graphically in Fig. 3.

---

## 3. GaAs Thickness Optimization

The thickness of the GaAs semiconductor layer was varied from **0.2 to 0.8 μm**.

The simulation showed that Jsc, FF, and PCE generally increased with increasing thickness, while Voc showed a slight decrease.

At a GaAs thickness of **0.8 μm**, the FF increased from approximately **81.8% to 82.5%**.

| Parameter | Value |
|---|---:|
| Thickness range | 0.2–0.8 μm |
| Selected thickness | 0.8 μm |
| FF at selected thickness | 82.5% |

The paper does not provide all individual numerical values from Fig. 6 in the text.

---

## 4. GaAs Doping Density Optimization

The GaAs acceptor density was varied from:

`1 × 10¹⁵ to 1 × 10¹⁸ cm⁻³`

Voc increased from approximately **1.02 to 1.03 V** across the investigated range.

The best performance was obtained at:

`5 × 10¹⁶ cm⁻³`

| Parameter | Value |
|---|---:|
| Doping density range | 1 × 10¹⁵–1 × 10¹⁸ cm⁻³ |
| Optimum acceptor density | 5 × 10¹⁶ cm⁻³ |
| Voc | ~1.03 V |
| FF | 82.9% |
| PCE | 23.4% |

---

## 5. Hole Transport Layer (HTL) Selection

Four HTL materials were compared:

- MoO₃
- Cu₂O
- CuI
- NiO

NiO provided the highest PCE among the investigated HTLs.

| HTL | PCE (%) |
|---|---:|
| MoO₃ | — |
| Cu₂O | — |
| CuI | — |
| NiO | 22.89 |

The paper reports that Voc and Jsc changed only slightly between the HTL materials. The complete numerical comparison is presented in Fig. 9.

---

## 6. Electron Transport Layer (ETL) Selection

Four ETL materials were investigated:

- PCBM
- CeOₓ
- ZnSe
- WS₂

ZnSe provided the best overall performance.

| ETL | Jsc (mA/cm²) | PCE (%) |
|---|---:|---:|
| PCBM | — | — |
| CeOₓ | — | — |
| ZnSe | 30.16 | 27.05 |
| WS₂ | — | — |

ZnSe was selected because it provided the highest reported Jsc and PCE among the investigated ETLs.

---

## 7. ETL Thickness Optimization

The ZnSe ETL thickness was varied at:

`0.01, 0.05, 0.08, 0.10, and 0.30 μm`

The open-circuit voltage showed little variation across the investigated thicknesses.

For the first four thicknesses (0.01–0.10 μm), Jsc remained approximately similar. At 0.30 μm, Jsc decreased to **30.14 mA/cm²**.

The highest PCE was obtained with a ZnSe thickness of **0.01 μm**.

| ZnSe thickness (μm) | Jsc (mA/cm²) | PCE (%) |
|---:|---:|---:|
| 0.01 | ~constant | 27.10 |
| 0.05 | ~constant | — |
| 0.08 | ~constant | — |
| 0.10 | ~constant | — |
| 0.30 | 30.14 | — |

Only the explicitly reported numerical values are included here.

---

## 8. ETL Doping Density Optimization

The ZnSe donor density was investigated over:

`1 × 10¹⁵ to 1 × 10²⁰ cm⁻³`

Voc remained approximately **1.03 V** throughout the range.

Jsc remained close to **30.17 mA/cm²**, except at `1 × 10²⁰ cm⁻³`, where it decreased to **30.10 mA/cm²**.

The optimum donor density was:

`5 × 10¹⁷ cm⁻³`

| Parameter | Value |
|---|---:|
| Doping density range | 1 × 10¹⁵–1 × 10²⁰ cm⁻³ |
| Optimum donor density | 5 × 10¹⁷ cm⁻³ |
| Voc | ~1.03 V |
| Jsc | ~30.17 mA/cm² |
| FF | 87.2% |
| PCE | 27.12% |

---

## 9. CsBi₃I₁₀ Thickness and Doping Density Optimization

The CsBi₃I₁₀ absorber layer was optimized by varying its thickness and shallow acceptor density.

The best combination was:

- Thickness: **0.2 μm**
- Shallow acceptor density: **1 × 10¹⁴ cm⁻³**

At this point, the optimized device achieved:

| Parameter | Value |
|---|---:|
| CsBi₃I₁₀ thickness | 0.2 μm |
| Acceptor density | 1 × 10¹⁴ cm⁻³ |
| Voc | 1.03 V |
| Jsc | 30.2 mA/cm² |
| FF | 88.1% |
| PCE | 27.40% |

The highest Voc reported in this optimization was **1.32 V**, obtained at a CsBi₃I₁₀ thickness of **1.0 μm** and an acceptor density of **1 × 10¹⁸ cm⁻³**.

At the same thickness and acceptor density, the PCE decreased to approximately **5.7%**.

---

## 10. Back Contact Work Function and Temperature

The effect of back-contact work function and operating temperature was investigated using Al as the back contact.

The optimized condition was:

- Temperature: **275 K**
- Work function: **5.8 eV**

The study reports:

| Parameter | Reported result |
|---|---|
| Selected temperature | 275 K |
| Selected work function | 5.8 eV |
| Maximum reported Voc | 1.071 V |
| Maximum Jsc region | 325 K, work function 4.8–5.8 eV |
| Highest PCE region | 275 K, work function 4.8–5.8 eV |

The final work function was selected as **5.8 eV** at **275 K**.

---

## 11. Final Optimized Device

After the sequential optimization of the semiconductor, HTL, ETL, absorber layer, and back contact, the final device structure was:

`Al / NiO / GaAs / CsBi₃I₁₀ / ZnSe / ITO`

The final simulated photovoltaic performance was:

| Parameter | Final value |
|---|---:|
| Voc | 1.03 V |
| Jsc | 30.2 mA/cm² |
| FF | 88.1% |
| PCE | 27.40% |

---


