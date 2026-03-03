🔍 Project Overview
The primary objective of this analysis is to model and compare recovery trends across different population cohorts. Using datasets representing recovery times (in days), this project explores:
Central Tendency: Estimating population mean recovery times.
Inferential Statistics: Calculating 95% Confidence Intervals using 
-distributions.
Hypothesis Testing: Comparing recovery rates between international cohorts (e.g., NSW vs. Israel) to identify statistically significant geographic differences.
🛠️ Tech Stack & Methodology
Language: R (v4.x)
Reporting: Quarto (Markdown-based reproducible documentation)
Libraries: dplyr for data manipulation, ggplot2 for visualization.
Statistical Techniques:

-tests for difference in means with unknown variances.
Poisson modeling for recovery duration predictions.
Data cleaning and standard error calculations.
📁 Repository Structure
index.qmd: The primary Quarto source code containing all analysis and R scripts.
index.html: The fully rendered, recruiter-ready report.
covid.recovery.2025.csv: Primary dataset for recovery time estimation.
israeli.covid.19.ass2.csv: Comparative dataset for hypothesis testing.
.gitignore: Configured to exclude local R environment clutter.
📈 Key Insights
Calculated a sample mean recovery time of 14.215 days from a sample size of 
.
Established a 95% confidence interval for recovery duration, providing a statistically sound range for public health expectations.
[Optional: Add a one-sentence finding from your hypothesis test results here].
