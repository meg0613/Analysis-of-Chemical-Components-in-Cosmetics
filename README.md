# Analysis of Chemical Components in Cosmetics

## Project Overview

This project presents a comprehensive analysis of the chemical components present in cosmetic products and evaluates their relationship with factors such as brand performance, pricing strategies, and product rankings. The primary goal was to identify ingredient trends, explore co-occurrence patterns, and develop visual and analytical insights that could be used by businesses, researchers, and consumers.

The project integrates multiple tools and platforms to ensure well-rounded deliverables, including interactive dashboards, exploratory data analysis, advanced visualization, and detailed reports.

---

## Tools and Technologies

* **Programming Languages**: R, Python, SQL
* **R Libraries**: tidyverse, ggplot2, flexdashboard, plotly, Rtsne, wordcloud2, corrplot, treemapify
* **Python Libraries**: pandas, numpy, matplotlib, seaborn, scikit-learn
* **Visualization Tools**: Excel, Tableau, Google Sheets
* **Documentation and Reporting**: RMarkdown, Jupyter Notebook, Microsoft Word

---

## Methodology and Approach

1. **Data Collection and Preparation**

   * Dataset was imported and cleaned for inconsistencies.
   * Duplicates were removed and ingredient naming standardized.
   * Numeric fields such as *Price* and *Rank* were converted and validated.

2. **Exploratory Data Analysis (EDA)**

   * Descriptive statistics and summary tables were created to highlight key variables.
   * Price distributions, product ranks, and ingredient counts were analyzed.
   * Ingredient tokenization allowed deeper investigation of frequently occurring chemical compounds.

3. **Advanced Analytical Techniques**

   * **Ingredient Co-occurrence Analysis**: Co-occurrence matrices and heatmaps were generated to highlight common ingredient combinations.
   * **Dimensionality Reduction with t-SNE**: Applied t-SNE on ingredient vectors to map similarity between products and identify clustering patterns.
   * **Correlation Analysis**: Examined relationships between price, product rank, and ingredient count.

4. **Dashboard Development**

   * **R Flexdashboard**: Interactive dashboard with brand filters, ingredient search, t-SNE visualizations, and word cloud analysis.
   * **Excel Dashboard**: KPI-driven dashboard with pivot charts, slicers, and performance tracking for products and brands.
   * **Tableau Dashboard**: Designed for additional interactive visuals (optional expansion).

5. **Reporting**

   * A **business-focused report** was created to highlight insights for decision-makers.
   * An **academic-style report** was developed to emphasize methodology, tools, and detailed analysis.

---

## Key Features

* **Ingredient Analysis**: Identification of the most frequently used ingredients and their variations across brands.
* **Brand Share Analysis**: Treemaps and pie charts illustrating brand dominance and distribution of products.
* **Word Clouds**: Visualization of ingredient frequency for quick interpretability.
* **Correlation Heatmaps**: Quantifying relationships between price, rank, and ingredient count.
* **t-SNE Mapping**: Clustering of products with similar ingredient compositions.
* **Interactive Data Exploration**: Through Excel slicers and R Shiny dashboard filters.

---

## Deliverables

1. **Interactive R Flexdashboard** – A web-based interactive dashboard for ingredient, price, and brand analysis.
2. **Excel Dashboard** – A professional dashboard with KPIs, interactive slicers, and pivot-driven charts.
3. **Jupyter Notebook** – An end-to-end analysis notebook covering data cleaning, preprocessing, EDA, and machine learning.
4. **GitHub Repository** – All project files, dashboards, and reports for reproducibility and transparency.

---

## Results and Insights

* Certain ingredients, such as *water, glycerin, and niacinamide*, were identified as dominant in cosmetic formulations.
* Price did not always correlate with better product ranking, suggesting that brand marketing and perception play a major role.
* Ingredient co-occurrence heatmaps revealed common chemical combinations used across brands.
* t-SNE mapping provided visual clusters of products, demonstrating similarity in composition and potential areas of competitive overlap.
* Brand analysis highlighted leading companies with high product counts and premium pricing strategies.

---

## How to Run

1. Clone this repository:

   ```bash
   git clone https://github.com/username/cosmetics-analysis.git
   ```

2. To launch the R Flexdashboard:

   ```r
   rmarkdown::run("dashboard/cosmetics_dashboard.Rmd")
   ```

3. To explore the Jupyter Notebook:

   ```bash
   jupyter notebook notebooks/cosmetics_analysis.ipynb
   ```

4. To use the Excel dashboard, open the file:

   ```bash
   excel_dashboard/cosmetics_dashboard.xlsx
   ```

---

## Future Enhancements

* Integration of customer review data for **sentiment analysis**.
* Development of a **predictive machine learning model** for ranking prediction.
* Expansion of dashboards to include **Power BI** for additional visualization capabilities.
* Segmentation of analysis into **skincare vs. makeup categories** for more targeted insights.

---

## Author

**Meghna Chaturvedi**
Data Analyst | Business Analytics Enthusiast

