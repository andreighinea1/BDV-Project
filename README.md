# Global Terrorism Analysis

**Course**: Machine Learning (M1, S2)  
**Team**: **_Ghinea Andrei-Robert_** & **_Diaconu Bianca_**  
**Dataset**: [Global Terrorism Database (GTD)](https://www.kaggle.com/datasets/START-UMD/gtd)

This repository contains a Jupyter notebook that explores the Global Terrorism Database (GTD) and generates a series of
visualizations showing terrorist activity over time and across regions.

---

## Dependencies

All required packages are listed in `requirements.txt`. To install:

```bash
pip install -r requirements.txt
```

---

## How to Run

1. Clone or download this repository.

2. Launch Jupyter and open `gtd_analysis.ipynb`:

   ```bash
   jupyter notebook gtd_analysis.ipynb
   ```

3. Execute all cells in order—no manual data download is needed.

---

## Visualization Structure of Results

- **Number of Terrorist Attacks per Year**
- **Correlation between Attacks and Fatalities per Year**
- **Monthly Seasonality of Attacks**
- **Top 25 Countries by Number of Attacks (Word Cloud)**
- **Terrorist Attacks per Year by Region**
    - **Continuous “Heatmap” of Attacks by Year & Region (Top 5 + Other)**
    - **Average Terrorist Attacks per Year by Region (Top 5 + Other)**
- **Global Terrorist Attacks by Country (Choropleth via Plotly)**
- **Top 10 Terrorist Groups by Number of Attacks**
- **Attacks per Year for Top 5 Terrorist Groups**
