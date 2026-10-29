# nhl-team-performance-analysis-
Exploratory analysis of actual and expected goal differentials across NHL teams in the 2025–26 regular season.
# NHL Team Performance Analysis — 2025–26

## Project overview

This project examines how actual goal differential compares with expected goal differential across 32 NHL teams during the 2025–26 regular season. Using Python, pandas and Matplotlib, I cleaned and checked the team-level data, calculated performance differentials, and created visual comparisons.

## Research question

How closely did actual NHL team goal differentials align with expected goal differentials during the 2025–26 regular season?

## Methods

- Inspected the dataset's structure, team coverage, missing values and duplicate rows.
- Selected the overall (`all`) statistics for each team.
- Calculated actual goal differential as goals for minus goals against.
- Calculated expected goal differential as expected goals for minus expected goals against.
- Calculated shot differential as shots on goal for minus shots on goal against.
- Used a scatter plot and Pearson correlation to examine the relationship between actual and expected goal differential.

## Key findings

The Pearson correlation between actual and expected goal differential was 0.807, indicating a strong positive linear association in this dataset.

Colorado recorded the highest actual goal differential (+101), compared with an expected differential of +69.79. Buffalo's actual differential (+43) was substantially higher than its expected differential (−6.46). New Jersey showed the opposite pattern, with an actual differential of −27 and an expected differential of +11.73.

These differences highlight variation between actual results and expected-goal measures. The analysis is descriptive and does not establish the causes of those differences.

## Visualisations

The `charts` folder contains:

1. Actual goal differential by team
2. Expected goal differential by team
3. Shot differential by team
4. Actual versus expected goal differential

## Tools

- Python
- pandas
- NumPy
- Matplotlib
- Google Colab

## Data source

Team-level NHL statistics from MoneyPuck. Please consult the original source for its data definitions, attribution requirements and permitted uses.

## Limitations

This analysis compares team-level season totals. It does not establish causation, assess individual players, or account for every factor that can influence scoring outcomes. Expected goals are model-based estimates, not observed goals.

## Reproducibility

The analysis notebook contains the data checks, calculations and visualisations. To reproduce the analysis, obtain the source dataset, make it available to the notebook, and run the cells in order.

## Author

Independent analytics project.
