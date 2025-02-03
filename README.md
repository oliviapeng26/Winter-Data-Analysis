# Winter Data Analysis Challenge 2024 - 🥉 Place

**Impact of Financial Healthcare Investment on Global Life Expectancy Over the Past 150 Years**

This project, created by Olivia Peng and Angel Poi, explores the relationship between healthcare investments and life expectancy through visualisations statistical analyses. Our findings provide insights into how personal habits, government spending, and private R&D influence global health outcomes.

---

## Executive Summary
- **Research Question:** How does financial investment in healthcare-related areas influence life expectancy over the past 150 years globally?
- **Key Findings:**
  1. **Obesity vs. Life Expectancy:** 
     -  High obesity rates negatively correlate with life expectancy, yet life expectancy continues to grow yearly.  
     - Statistical conclusion: *p = 2.2 × 10⁻¹⁶* (reject null of no statistical relationship).  
  2. **Private Medical R&D Investments (2013-2023):**  
     - Investment doubled from $20M (2013) to $40M (2019), leading to a modest increase in life expectancy (72.06 → 73.39 years). However, life expectancy dropped beyond 2019 possibly due to COVID-19. 
     - R&D investments have a long-term impact (p = 0.051 > 0.05).  
  3. **Government Expenditure:**  
     -  A general positive relationship between health and education expenditure, and an increasingly greater life expectancy as both expenditures increase.
     - Countries with lower investment in healthcare exhibit lower life expectancy.

---

## Features
- **Data Scope:** Global life expectancy, obesity, medical R&D investment, and government expenditure data from the past 150 years.
- **Statistics and Visuals:**

| Key finding  | Statistical Analysis  | Visualisations  |
|-----------|-----------|-----------|
| 1 | Linear regression | Temporal scatterplots |
| 2 | ANOVA test | Temporal scatterplot, Stacked bar chart |
| 3 | Linear regression (insufficient data) | Bubble plots |


---

## Project Structure
The project is organised into the following folders:

- **data/:** Contains CSV files with all data used in this project.
- **scripts/:** Contains R Markdown (.Rmd) file with code.
- **reports/:** Contains the final HTML report and PPT presentation.

---

## Technologies Used
- **R and RMarkdown:** For statistical analysis and reporting.
- **ggplot2 and plotly:** For creating interactive visualisations.
- **Microsoft PowerPoint:** For presenting findings.

---

## Installation
To view the full analysis, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Winter-Data-Analysis.git
2. Open the Data-Analysis-Challenge.html file in a web browser to view the report.
3. For the full R code:
- Install R and RStudio.
- Open the Data Analysis Challenge.Rmd file in RStudio.
- Run the code to reproduce the analysis.

---

## Usage
- **Summary of Findings:** Open `Winter-Data-Analysis-PPT.pdf` file on desktop to skim project structure.
- **Interactive Report:** Open `Data-Analysis-Challenge.html` in your browser to explore and interact with the findings.
- **Reproducible Analysis:** Run the `Data Analysis Challenge.Rmd` file in RStudio to reproduce results and customise analyses.

---

## Acknowledgments
- Special thanks to the University of Sydney and Sydney Precision Data Science Centre for organising the Winter Data Analysis Challenge.
- Inspired by the United Nations Sustainable Development Goals (UN SDGs).

---

## License
This project is licensed under the MIT License - see the LICENSE file for details.

---

## Contact
Created by **Olivia Peng**. Feel free to reach out :)
