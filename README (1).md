# 💧 UNICEF Sanitation Report — Global Access to Improved Sanitation Facilities

A UNICEF data analytics report examining the proportion of the global population with access to improved sanitation facilities (2000–2024), built with Quarto, plotnine, and Polars.

## 🔗 Live Report

> **[View the live report on GitHub Pages](https://your-username.github.io/unicef-sanitation/)**  
> *(Replace with your actual URL after publishing)*

## 📊 What's Inside

The report includes:
- **World Map** — Global sanitation access distribution (latest year per country)
- **Bar Chart** — The 20 most-deprived nations
- **Scatterplot** — GDP per capita vs. sanitation access with regression line
- **Time Series** — 24-year trends for 10 representative countries

## 📁 File Structure

```
unicef_sanitation_report/
├── index.qmd                          # Main Quarto report
├── custom.css                         # Light blue / royal blue stylesheet
├── _quarto.yml                        # Quarto project configuration
├── requirements.txt                   # Python package requirements
├── unicef_indicator_3.csv             # UNICEF sanitation indicator data
├── unicef_metadata_3.csv              # UNICEF country metadata
├── UNICEF_Sanitation_Render_and_Publish.ipynb  # Google Colab notebook
└── docs/                              # Rendered HTML output (GitHub Pages)
    └── index.html
```

## 🚀 How to Render

### Option A: Google Colab (Recommended)
1. Upload this folder to Google Drive
2. Open `UNICEF_Sanitation_Render_and_Publish.ipynb` in Colab
3. Follow the steps to install Quarto, render, and push to GitHub Pages

### Option B: Local
```bash
pip install polars plotnine numpy pandas scipy
quarto render index.qmd
```

## 📚 Data Sources

| Dataset | Source |
|---------|--------|
| Sanitation Indicator | [UNICEF Data](https://data.unicef.org/topic/water-and-sanitation/sanitation/) |
| Country Metadata (GDP, Life Expectancy, Population) | [UNICEF / World Bank](https://databank.worldbank.org) |
| JMP WASH Data | [washdata.org](https://washdata.org) |

## 📜 License

Data: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) — UNICEF  
Report: Academic submission — DCU BAA1030
