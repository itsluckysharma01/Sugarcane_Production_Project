# Sugarcane Production Project

Interactive analysis notebook for exploring global sugarcane production patterns, comparing countries and continents, and reviewing relationships between production, acreage, yield, and per-person metrics.

## Quick Links

- [Notebook](Project_Sugarcan_Prediction.ipynb)
- [Dataset](List%20of%20Countries%20by%20Sugarcane%20Production.csv)
- [Workflow](#workflow)
- [Key Findings](#key-findings)
- [Notebook Map](#notebook-map)
- [How to Run](#how-to-run)

## Overview

This project uses a Jupyter notebook to clean, explore, and visualize sugarcane production data. The notebook covers country-level ranking, continental comparisons, top producers, yield analysis, acreage analysis, and correlation checks across the main numeric features.

<details open>
<summary><strong>What this project answers</strong></summary>

- Which countries produce the most sugarcane.
- How production differs across continents.
- How acreage, yield, and per-person production relate to each other.
- Which countries stand out in the top and bottom ranges of the dataset.

</details>

<details>
<summary><strong>Project files</strong></summary>

- <strong>Project_Sugarcan_Prediction.ipynb</strong> - full analysis notebook.
- <strong>List of Countries by Sugarcane Production.csv</strong> - source dataset.
- <strong>README.md</strong> - project overview and usage guide.

</details>

## Workflow

<details open>
<summary><strong>Analysis pipeline</strong></summary>

1. Load the dataset into pandas.
2. Inspect the structure and clean the data.
3. Build summary tables for countries, continents, and production metrics.
4. Visualize rankings and distributions with plots.
5. Compare production with acreage, yield, and per-person values.
6. Review correlation patterns across numeric columns.

</details>

## Key Findings

<details>
<summary><strong>Notebook highlights</strong></summary>

- The notebook builds multiple ranked views such as top countries, top production, top acreage, and top yield.
- It compares continental production and country counts.
- It includes several visualizations for distribution, comparison, and correlation analysis.
- The notebook execution history shows the analysis completed successfully through the final summary cells.

</details>

## Notebook Map

<details open>
<summary><strong>Sections inside the notebook</strong></summary>

- Data loading and initial inspection.
- Data cleaning and validation.
- Country ranking and top producers.
- Continental analysis.
- Acreage, yield, and per-person comparisons.
- Correlation matrix and plots.
- Final summary visuals.

</details>

## How to Run

1. Open `Project_Sugarcan_Prediction.ipynb` in VS Code or Jupyter.
2. Make sure the CSV file stays in the same folder as the notebook.
3. Run the notebook cells from top to bottom.

If you want to use a local Python environment, install the usual notebook stack first:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

## Suggested Next Steps

- Add a short interpretation section below each major plot in the notebook.
- Export the notebook as HTML if you want a shareable static report.
- Add a requirements file if you want the environment to be fully reproducible.

