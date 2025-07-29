# sales-analysis-python-powerbi
Data analytics project using Python and Power BI# 

📊 Revenue Analysis Project

This project analyzes revenue data by region and product using R, ggplot2, and R Markdown.

## 📁 Project Structure

- `scripts/sales_analysis.R` — Summary & plots generation
- `report.Rmd` — R Markdown report (generates HTML/PDF)
- `images/` — Folder for saved plots
- `*.csv` — Exported summary data

## 📦 Requirements

- R, RStudio
- Packages: `dplyr`, `ggplot2`, `readr`, `rmarkdown`, `shiny` (optional)

## 📈 Output

- `region_summary.csv`, `product_summary.csv`
- `images/revenue_by_region.png`
- `report.html` and `report.pdf`

## 🚀 How to Run

```r
source("scripts/sales_analysis.R")
rmarkdown::render("report.Rmd")

