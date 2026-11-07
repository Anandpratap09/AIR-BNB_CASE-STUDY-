# Airbnb NYC: Exploratory Data Analysis

Analyzes 48,895 New York City Airbnb listings (2019) to advise Airbnb on where to focus as travel recovers after COVID-19.

## Business questions

- Which neighbourhoods should Airbnb target?
- What price ranges do customers prefer?
- How do room type, price, availability and reviews relate?

## Approach

1. Data wrangling: `last_review` and `reviews_per_month` are missing about 20.6% of values, and `name` and `host_name` about 0.3 to 0.4%. Nothing was dropped or imputed because the goal is analysis, not modelling.
2. Univariate analysis
3. Bivariate and multivariate analysis: room type against review category and price category, availability against price against reviews

## Key findings

- About 81% of listings are in Manhattan and Brooklyn
- Listings with very high availability and very low price tend to get more reviews per month

## Files

| File | Purpose |
| --- | --- |
| `AIRBNB Case Study.ipynb` | Full analysis |
| `AB_NYC_2019.csv` | Dataset |
| `Airbnb NYC Storytelling Assignment_1.pdf`, `Airbnb NYC Storytelling Case Study_2.pdf` | Presentation write-ups |
| `DATA METHODOLOGY.pdf` | How the analysis was done |

## Stack

Python, pandas, matplotlib, seaborn
