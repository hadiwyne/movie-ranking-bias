# Movie Rating Inflation/Bias Analysis

This project explores potential rating inflation in **Fandango star ratings**, inspired by an article by Walt Hickey from FiveThirtyEight. The goal of the analysis is to confirm whether Fandango improved their rating system after Walt's article exposing the inflation of their rating system, by comparing 2015's ratings with those of 2016. Additionally, we compared **Fandango star ratings** with **Rotten Tomatoes'** to further emphasis this inflation, and to confirm whether Fandango's system improved in the following year or not. The analysis is done using basic Python and pandas, with data visualization using Matplotlib.

## Files

- `Rating_Inflation.ipynb`: Jupyter notebook performing the analysis.
- `fandango_score_comparison.csv`: Dataset containing Fandango scores and scores from other movie rating sites for various movies for the year **2015**.
- `movie_ratings_16_17.csv`: Dataset containing Fandango scores and scores from other movie rating sites for various movies for the year **2016**.

## Objective

The goal of this notebook is to:

- Compare the distribution of Fandango's ratings from the year 2015 - 2016.
- Detect evidence of inflation or bias in Fandango ratings.
- Confirm whether Fandango has improved their rating system in the following year.
- Compare Fandango's ratings system to another more popular website like Rotten Tomatoes
- Visualize the differences using Kernel Density Estimation (KDE) and Bar plots.

## Tools & Libraries

- Python 3
- pandas
- matplotlib

## Methods

1. **Data Loading**: Read movie ratings from a CSV file.
2. **Data Cleaning and Feature Engineering**: Select relevant columns and engineer features for better analysis.
3. **Visualization**: KDE and Bar plots are generated to compare the two distributions.
4. **Interpretation**: The visual output helps identify whether Fandango ratings tend to be inflated.
5. **Comparison**: Fandango's rating system is compared to that of Rotten Tomato's to further emphasize the inflation.


## How to Run

1. Clone or download the repository.
2. Ensure you have Python and Jupyter installed.
3. Open the notebook `Rating_Inflation.ipynb` in Jupyter.
4. Run all cells to see the analysis and plot.

```bash
pip install pandas matplotlib
jupyter notebook Rating_Inflation.ipynb
