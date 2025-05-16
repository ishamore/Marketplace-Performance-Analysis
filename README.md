# Marketplace-Performance-Analysis
# Google Play Store App 

This project analyzes over 10,000 Android apps on the Google Play Store using Python for data wrangling and Tableau for data storytelling.

## Dashboard

[View the Tableau Dashboard](https://public.tableau.com/app/profile/isha.more/vizzes)

## Key Questions Answered

- How are apps distributed across categories?
- Do free apps get better ratings than paid apps?
- What's the relationship between installs, price, and reviews?
- Which categories and genres dominate the store?
- How often are top-rated apps updated?

## Tools Used

- **Python**: Pandas, Seaborn, Matplotlib for EDA & preprocessing
- **Tableau**: Interactive dashboard and visual storytelling
- **Git/GitHub**: Version control & project hosting

## Data Cleaning Steps

- Converted `Installs`, `Price`, and `Reviews` to numeric
- Cleaned `Size` column (standardized MB)
- Removed rows with missing or corrupt entries
- Normalized text fields (`Genres`, `Category`, etc.)

## Feature Engineering

- App Age (from `Last Updated`)
- Install Buckets (e.g., 1M–5M, 5M–10M)
- Price Category (Free vs Paid)

## Project Structure

Marketplace Performance -Analysis/
data/
notebooks/
images/
README.md
