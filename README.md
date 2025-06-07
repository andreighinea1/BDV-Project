# Global Terrorism Analysis

**Exploratory data analysis of the Global Terrorism Database (1970–2017) with interactive and static Python visualizations.**

**Course:** Machine Learning (M1, S2)  
**Team:** **_Ghinea Andrei-Robert_** & **_Diaconu Bianca_**  
**Dataset:** [Global Terrorism Database (GTD)](https://www.kaggle.com/datasets/START-UMD/gtd)

This repository contains a Jupyter notebook that analyzes the Global Terrorism Database (GTD), generating interactive
and static visualizations to highlight terrorist activity trends across time, regions, and groups.

---

## Project Paper

A detailed scientific paper documenting the methodology, results, and discussion for this analysis is included in the
repository:

* [Global Terrorism Analysis.pdf](Paper/Global%20Terrorism%20Analysis.pdf) — *Final report with all figures, findings,
  and references.*
* All Overleaf (LaTeX) source files are located in the [Paper](Paper) directory.

---

## Dependencies

* All required Python packages are listed in [`requirements.txt`](requirements.txt).
* Install them with:
    ```bash
    pip install -r requirements.txt
    ```
* This project was tested with **Python 3.11**.

---

## How to Run

1. **Clone or download this repository.**
2. **Launch Jupyter and open the notebook:**
    ```bash
    jupyter notebook gtd_analysis.ipynb
    ```
3. **Execute all cells in order.**

---

## Visualization Structure

* **Number of Terrorist Attacks per Year**
* **Correlation between Attacks and Fatalities per Year**
* **Monthly Seasonality of Attacks**
* **Top 25 Countries by Number of Attacks (Word Cloud)**
* **Terrorist Attacks per Year by Region**
    * Continuous “Heatmap” of Attacks by Year & Region (Top 5 + Other)
    * Average Terrorist Attacks per Year by Region (Top 5 + Other)
* **Global Terrorist Attacks by Country (Choropleth via Plotly)**
* **Top 10 Terrorist Groups by Number of Attacks**
* **Attacks per Year for Top 5 Terrorist Groups**

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
