# Data Analytics project about -Music-billboard-hot-100-year-end-tracks-in-the-US

## About Dataset

Every song on Billboard's Year-End Hot 100 from 2000 to 2024 (2,484 chart entries, 2,246 unique tracks). Each song is matched to Spotify audio features and an iTunes genre, given LLM-assigned lyric topics, and scored with lyric metrics, n-gram counts, and NRC emotion word counts.
https://www.kaggle.com/datasets/matthewwilliams333/billboard-hot-100-year-end-tracks-2000-2024

## Kaggle path 

"matthewwilliams333/billboard-hot-100-year-end-tracks-2000-2024"

## What is EDA?

Exploratory Data Analysis (EDA) is the systematic process of examining, summarizing, and visualizing data before formal modeling or hypothesis testing. It is the first and most critical stage of any data analytics workflow.


## Project Structure

```
├── data/
│   ├── raw/            # Original, immutable data
│   └── processed/      # Cleaned and transformed data
├── notebooks/
│   ├── note1.ipynb
├── src.txt
├── outputs/
│   └── figures/        # Saved plots and summaries
│   └── reports/        # Saved data for visuls
├── requirements.txt
└── README.md
```

## EDA Workflow in This Project

1. **Data overview** — shape, dtypes, sample rows, summary statistics.
2. **Missing value analysis** — counts, patterns, and imputation strategy.
3. **Univariate analysis** — histograms, box plots, value counts for each variable.
4. **Bivariate analysis** — scatter plots, grouped summaries, correlation heatmaps.
5. **Outlier detection** — IQR and z-score methods with visual inspection.
6. **Data quality report** — documented findings and decisions.
