# Social Media Engagement Analysis

A data analysis project examining 90 days of cross-platform social media performance — Instagram, YouTube, Twitter/X, and TikTok — using Python.

![Dashboard Preview](images/social_dashboard.png)

## Overview

This project walks through a complete data analysis workflow:

1. **Data cleaning & validation** — checking for missing values, duplicates, and invalid entries
2. **Feature engineering** — calculating engagement and engagement rate metrics
3. **Exploratory analysis** — summary statistics across platforms
4. **Comparative analysis** — weekday vs. weekend engagement patterns
5. **Visualization** — a 5-chart dashboard summarizing key trends
6. **Insights & recommendations** — actionable takeaways based on the findings

## Key Findings

- **TikTok had the highest engagement rate (7.0%)**, more than 3x Twitter/X (2.1%)
- **YouTube showed the steadiest performance**, with the second-highest engagement rate (5.0%)
- **Weekend posting showed minimal uplift** overall — impact varies by platform
- **TikTok and Instagram drove the fastest follower growth** over the quarter

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib

## Project Structure

```
social-media-engagement-analysis/
├── analysis.ipynb          # Main analysis notebook
├── data/
│   └── social_engagement_data.csv
├── images/
│   └── social_dashboard.png
└── README.md
```

## How to Run

```bash
pip install pandas numpy matplotlib
jupyter notebook analysis.ipynb
```

## Note

This project uses synthetically generated data to demonstrate an end-to-end analysis workflow. The same cleaning, analysis, and visualization process shown here is applied to real client datasets in my freelance work.


