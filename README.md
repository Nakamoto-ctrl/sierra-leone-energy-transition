# AI, Big Data, and Sierra Leone's Energy Transition
### A Data-to-Decision Framework for Utility Reform and Distributed Electrification

**Authors:** Jeremy Thoronka & Mohamed Alpha (2025)  
**Project:** *Cities: Smarter Futures*

---

## Overview

This repository contains the complete analytical pipeline and manuscript source for the study on Sierra Leone's energy transition. The research introduces the **AI--Big Data Catalyst Model for Sierra Leone (AIBD-Cat-SL)**, a four-layer sociotechnical architecture designed to bridge the data-to-decision gap in LMIC energy systems.

### Key Contributions
*   **Double Blindspot Index (DBI):** Mapping the spatial co-location of energy deprivation and data invisibility (r = 0.972).
*   **Data Readiness Index (DRI):** A PCA-weighted assessment of district-level suitability for AI integration.
*   **Algorithmic Bias Audit:** The first LMIC demographic parity audit for electrification planning, demonstrating a 92% parity gap reduction through Layer 4 governance constraints.
*   **Monte Carlo Validation:** Robustness testing across 15,000+ simulations covering DBI stability, parity thresholds, and NTL revenue recovery.

---

## Repository Structure

- `AIBD_Production_Notebook.ipynb`: The primary Jupyter Notebook containing the data processing, machine learning models (Random Forest, Isolation Forest), and Monte Carlo simulations.
- `Cities_Smarter_Futures_Manuscript.tex`: The LaTeX source code for the 23-page manuscript.
- `Results_and_Figures/`: A production-ready directory containing:
    - **14 High-Resolution Figures:** (.png) including 3 systemic framework diagrams.
    - **8 Analytical Datasets:** (.csv) including district-level DRI/DBI scores and MC results.
- `references.bib`: Complete BibTeX database for the research.

---

## Getting Started

### Prerequisites
The analysis is built using Python 3.12+ and requires the following libraries:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn geopandas scipy
```

### Reproducibility
To regenerate all figures and datasets:
1. Open `AIBD_Production_Notebook.ipynb` in any Jupyter environment.
2. Ensure the `Results_and_Figures/` directory exists.
3. Run all cells sequentially. The notebook is idempotent and will automatically update the `Results_and_Figures` manifest.

---

## Results Summary

| Metric | Result | Impact |
| :--- | :--- | :--- |
| **Parity Gap ($\Delta_{DP}$)** | 0.406 $\to$ 0.034 | **92% Reduction** in algorithmic bias |
| **DBI Correlation** | r = 0.972 | Confirms structural "Double Blindspot" |
| **DRI Critical Tier** | 7 of 14 Districts | Identifies foundational data investment needs |
| **P(Revenue $>$ $50K)** | 80.4% | Validates financial return on NTL analytics |

---

## Citation
If you use this project in your research, please cite:
> Thoronka, J. & Alpha, M. (2025). AI, Big Data, and Sierra Leone's Energy Transition: A Data-to-Decision Framework for Utility Reform and Distributed Electrification. *Cities: Smarter Futures*.

## License
MIT License - See the [LICENSE](LICENSE) file for details.
