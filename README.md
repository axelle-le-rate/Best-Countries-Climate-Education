# 🌍 Top Countries for Climate Adaptability, Education, & Cost of Living

## 📌 Project Overview
This project ranks countries based on their climate readiness, economic capacity, governance, health risks, higher education quality, and cost of living. The ranking is inspired by the ND-GAIN Index, which measures a country's ability to adapt to climate change.

Through data cleaning, standardization, and composite scoring, this analysis determines which countries provide the best balance of climate resilience, economic stability, and affordability—with the United Kingdom emerging as the top choice!

📄 **View the Full Analysis Report:**  
[To-The-United-Kingdom.Rmd](To-The-United-Kingdom.Rmd)

## 🗂️ Dataset
- Source: [University of Notre Dame](https://gain.nd.edu/our-work/country-index/)
- Data Sizes:
  - Arable Land Per Capita: 267 rows × 5 columns (13.3KB)
  - Cost of Living: 140 rows × 8 columns (6.72 KB)
  - Economic Capacity:  193 rows × 5 columns (9.46 KB)
  - Fresh Water: 267 rows * 5 columns (12.6 KB)
  - Health Risks: 193 rows * 5 columns (9.64 KB)
  - Higher Education Rankings: 79 rows * 3 columns (1.3 KB)
  - Current Readiness: 193 rows * 5 columns (9.7 KB)
  - Government Capacity: 193 * 5 columns (9.55 KB)
- Preprocessing: Merged multiple datasets, cleaned missing values, and standardized variables for fair comparison.
  
## 🏗️ Ranking Methodology
Countries were ranked based on a composite score derived from two key indices:

### 1️⃣ Readiness Rank (Positive Factors)

- Current Climate Readiness
- Economic Capacity
- Government Stability
- Higher Education Quality
  
### 2️⃣ Vulnerability Rank (Negative Factors)

- Health Risks
- Cost of Living
- Fresh Water Availability
- Arable Land Availability
  
## 📊 Final Composite Score Calculation:
- Readiness Rank - Vulnerability Rank = Composite Score
- Higher scores indicate countries that are well-prepared for climate change while offering economic stability and livability.

## 🔍 Key Findings
- The United Kingdom ranks #1 due to strong governance, top-tier education, and a balanced cost of living.
- Countries with high economic capacity & government stability generally rank higher.
- Affordable cost of living significantly impacts country rankings, as seen in adjusted composite scores.

## 🚀 How to Run the Project
1. **Clone the repo**:
```sh 
git clone https://github.com/axelle-le-rate/Climate-Ready-Countries-Ranking.git
```
2. **Install dependencies in R:
```r
install.packages(c("dplyr", "tidyr", "ggplot2", "readr", "scales"))
```
3. **Run the R script in RStudio or Jupyter Notebook with an R kernel.**

## ⚙️ Technologies Used
R · dplyr · tidyr · ggplot2 · readr · scales

## 📌 Future Improvements
- Expand dataset to include job opportunities & wages for further analysis.
- Integrate real-time climate change projections into the model.
- Allow users to adjust ranking weights based on personal priorities (e.g., prioritizing education over cost of living).

## 📝 Note on ChatGPT Assistance
During the development and debugging phases of this project, I referenced valuable conversations with ChatGPT that helped me resolve coding issues and improve the overall solution. Unfortunately, these conversations are no longer accessible due to platform limitations, so the specific details cannot be provided here. However, the guidance and debugging steps from those interactions were integral to the project.
