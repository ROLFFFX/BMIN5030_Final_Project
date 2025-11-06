# BMIN5030 Final Project

#### Overview

This project primarily investigates the association between early antibiotic administration and patient outcomes among ICU patients diagnosed with sepsis using the MIMIC-IV dataset. The study aims to evaluate whether earlier intervention is associated with improved outcomes which is defined through a range of metrics, such as in-hospital mortality rate, 30-day readmission rate, ventilator-free days, and organ dysfunction progression. The goal is to identify potential clinical implications for optimizing the sepsis management processes. Some of these discrepancies stem from challenges in accurately defining the onset of sepsis, handling the time discretization for data analysis, or confounding factors such as illness severity and treatment bias.

#### Introduction

Sepsis is a leading cause of death in intensive care units (ICUs) and continues to pose major challenges to clinicians due to its complexity. Early antibiotic administration has long been considered a cornerstone of sepsis treatment, based on evidence suggesting that delays in treatment may increase mortality and worsen organ function. However, the optimal timing of antibiotic administration remains controversial, as observational studies have produced mixed results.

This project is interdisciplinary, combining insights from biomedical informatics, clinical medicine, and data science. From a clinical perspective, the project draws on principles of critical care and infectious disease management to define sepsis onset, select relevant outcomes, and interpret physiological indicators such as acuity scores (e.g. SOFA) trajectories; from a informatics standpoint, it involves working with high-dimensional EHR data and addressing issues such as timestep discretization and alignment, causal inference modeling, and other data science practices for various data processing tasks.

#### References

- Liu VX, Fielding-Singh V, Greene JD, Baker JM, Iwashyna TJ, Bhattacharya J, Escobar GJ. The Timing of Early Antibiotics and Hospital Mortality in Sepsis. Am J Respir Crit Care Med. 2017 Oct 1;196(7):856–863. doi:10.1164/rccm.201609-1848OC.
  “Hourly delays in antibiotic administration were associated with increased odds of hospital mortality even among patients who received antibiotics within 6 hours.”
- Sendak MP, Ratliff W, Sarro D, Alderton E, Futoma J, Gao M, Nichols M, Revoir M, Yashar F, Miller C, Kester K, Sandhu S, Corey K, Brajer N, Tan C, Lin A, Brown T, Engelbosch S, Anstrom K, Elish MC, Heller K, Donohoe R, Theiling J, Poon E, Balu S, Bedoya A, O’Brien C. Real-World Integration of a Sepsis Deep Learning Technology Into Routine Clinical Care: Implementation Study. JMIR Med Inform. 2020 Jul 15;8(7):e15182.
  “Machine learning models are commonly developed to enhance clinical decision making, but successful integrations of machine learning into routine clinical care are rare.”
