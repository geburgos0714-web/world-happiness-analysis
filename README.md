# World Happiness Analysis (2016)

## Project Overview

This project explores the 2016 World Happiness dataset to investigate relationships between economic factors, generosity, family support, government trust, and happiness rankings across countries.

The analysis was completed as part of DSC 207: Python for Data Science at UC San Diego.

## Research Questions

1. Do countries with higher generosity values also tend to have higher GDP per capita values?
2. Do average government trust-related values differ across geographical regions?
3. Do countries with higher family support values tend to have better happiness rankings?

## Tools and Technologies

- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Jupyter Notebook / Google Colab
- Descriptive statistics, IQR, Pearson correlation, and exploratory data analysis

## Methodology

The project includes:

- Loading and exploring the 2016 World Happiness dataset.
- Examining dataset dimensions, variable types, and descriptive statistics.
- Identifying potential happiness score outliers using the interquartile range (IQR).
- Comparing average happiness scores across regions.
- Using scatterplots, bar charts, and correlation coefficients to investigate three research questions.

## Key Findings

**1. Generosity and GDP per Capita**

The analysis found essentially no linear correlation between generosity and GDP per capita (r ≈ -0.026).

**2. Government Trust and Region**

Average Trust (Government Corruption) values differed across regions. Australia and New Zealand had the highest regional average, while Central and Eastern Europe had the lowest.

**3. Family Support and Happiness Rank**

Family values showed a strong negative correlation with numerical happiness rankings (r ≈ -0.733). Countries with higher family values generally had better rankings, represented by lower rank numbers.

## Limitations and Ethical Considerations

This is an exploratory analysis using data from 2016. The observed correlations do not establish causal relationships.

Additionally, government corruption-related measures may not fully represent the complexity of corruption perceptions across countries. Regional comparisons should therefore be interpreted cautiously to avoid misleading generalizations.

## Repository Files

- `world_happiness_analysis.ipynb` — Python notebook containing the analysis and visualizations.
- `2016.csv` — Dataset used for the analysis.

## How to Run

1. Download or clone this repository.
2. Open `world_happiness_analysis.ipynb` in Jupyter Notebook or Google Colab.
3. Install the required Python libraries: `pandas`, `numpy`, `matplotlib`, and `seaborn`.
4. Ensure `2016.csv` is available in the notebook's working directory.
5. Run the notebook cells in order.

## Author

Gerardo Burgos

UC San Diego — Master of Data Science
