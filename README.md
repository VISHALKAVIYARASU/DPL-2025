# DPL 2025

This repository contains data science notebooks and scripts for analyzing global social, welfare, and trade risks, with a focus on youth unemployment and demographic-driven productivity impacts.

## Contents

- **task5.ipynb**
  For 5th task.
  Predicts which countries will have youth unemployment rates above 25% by 2030 under a global slowdown scenario, using historical data and machine learning/time series models.

- **tasks6_7.ipynb**
  For 6th and 7th task. 
  Assesses which countries' export sectors are most at risk from labour shortages due to ageing demographics, simulates productivity impacts of rising median age, and builds a global trade network graph to identify central countries and simulate network disruptions.

## Usage

1. **Clone the repository**  
   ```
   git clone https://github.com/yourusername/dpl2025.git
   cd dpl2025
   ```

2. **Install dependencies**  
   Recommended: Use a virtual environment.  
   ```
   pip install pandas matplotlib seaborn networkx scikit-learn statsmodels pmdarima
   ```

3. **Place data files**  
   Ensure all required CSV files (e.g., `Employment_Unemployment.csv`, `Social_and_welfare.csv`) are in the project folder.

4. **Run Notebooks**  
   Open the notebooks in JupyterLab, VS Code, or Colab and run cells sequentially.

## File Descriptions

### task5.ipynb

- Loads and preprocesses youth unemployment data.
- Visualizes historical trends.
- Builds regression and ARIMA models to forecast youth unemployment rates for 2030.
- Identifies countries predicted to exceed the 25% threshold.
- Includes visualizations and discussion of model limitations.

### tasks6_7.ipynb

- Integrates and cleans demographic and trade data from all CSVs in the workspace.
- Identifies countries at risk of labour shortages due to ageing (using life expectancy as a proxy).
- Simulates productivity impacts for increases in median age.
- Builds a simulated global trade network graph for 25 countries.
- Analyzes network centrality and simulates disruption scenarios.
- Provides policy recommendations and visualizations.

## Outputs

- Plots and tables summarizing key findings.
- PNG images of risk scores and trade network graphs are saved to the project folder.
