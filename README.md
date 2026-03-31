# Apprentice Workforce Analysis

A data analysis project exploring U.S. apprenticeship workforce trends using industry sector data, NAICS classifications, union affiliation, and geographic distribution.

## Overview

This project cleans, analyzes, and visualizes apprenticeship program data to uncover patterns across industries, subsectors, and regions. The analysis identifies which sectors are driving apprenticeship growth, how union vs. non-union programs compare, and where apprenticeship activity is concentrated geographically.

## Repository Structure

```
Apprentice-Workforce-/
│
├── work.ipynb                        # Main analysis notebook
├── work-checkpoint.ipynb             # Jupyter auto-save checkpoint
│
├── apprenticeship_data.xlsx          # Raw apprenticeship dataset
├── apprenticeship_data_cleaned.csv   # Cleaned dataset used for analysis
│
├── naics_industry_analysis.xlsx      # NAICS industry-level analysis output
├── sector_comparison.xlsx            # Sector-level comparison output
├── subsector_analysis.xlsx           # Subsector breakdown output
├── top_naics_codes.xlsx              # Top NAICS codes by apprenticeship volume
│
├── geographic_analysis.png           # Geographic distribution of apprenticeships
├── naics_sector_pie.png              # Pie chart of NAICS sector share
├── naics_sector_union_comparison.png # Union vs. non-union by sector
├── naics_subsectors.png              # Subsector breakdown visualization
├── naics_top_sectors.png             # Top sectors by apprenticeship count
├── sector_chart.png                  # Sector-level bar chart
├── subsector_analysis.png            # Subsector analysis visualization
├── subsector_chart.png               # Subsector bar chart
├── top_naics_codes.png               # Top NAICS codes visualization
└── union_analysis.png                # Union affiliation analysis chart
```

## Analysis Highlights

- **Industry Sector Breakdown** — Identifies which NAICS sectors host the most apprenticeship programs
- **Subsector Deep Dive** — Drills down into subsector-level patterns within top industries
- **Union vs. Non-Union Comparison** — Compares apprenticeship volume and distribution across union and non-union programs
- **Geographic Analysis** — Maps apprenticeship activity by region to identify concentration areas
- **Top NAICS Codes** — Ranks specific NAICS codes with the highest apprenticeship enrollment

## Technologies Used

- Python (Jupyter Notebook)
- pandas — data cleaning and transformation
- matplotlib / seaborn — data visualization
- openpyxl — Excel file export

## Author

**Kimani Phillips** — [GitHub](https://github.com/KimaniPhillips12)
