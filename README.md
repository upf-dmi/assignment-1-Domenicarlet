# Hands on I – Exploratory Data Analysis of COVID-19 Clinical Data

This repository contains the analysis for **Hands on I (DMI course)**.  
The objective of the project is to perform exploratory data analysis, reproduce published results, and critically compare findings using clinical data from COVID-19 patients.

The analysis is based on the dataset from the publication:  
**Proteomic and Metabolomic Characterization of COVID-19 Patient Sera**  
Shen et al., Cell (2020)

---

# Report

The full analysis report is available here:  
➡ **[Hands_on_I.html](Hands_on_I.html)**

The HTML report contains:
- Data loading, cleaning and preparation (Exercise 1)
    - Reproduction of Table 1 from the manuscript
    - Exploratory data analysis: missing data, normality, group comparisons, statistical tests
- Reproduction of Supplementary Figure S1 (Exercise 2)
    - Outlier identification and handling via winsorization
    - Comparison of results before and after outlier treatment
- Heatmap of clinical biomarkers with group and sex annotations (Exercise 3)
- Conclusion summarizing main findings across patient groups

The report is fully self-contained and includes all figures.

---

# Reproduce

To reproduce the analysis, open:

    Hands_on_I.Rmd

and run all cells. The data file `Table_S1.xlsx` should be placed in `data/raw_data/`.

---

# Authors

Cristina Torredemer Ortega (cristina.torredemer01@estudiant.upf.edu) and Domenica Arlet Teller Guardián (domenicaarlet.teller01@estudiant.upf.edu)
