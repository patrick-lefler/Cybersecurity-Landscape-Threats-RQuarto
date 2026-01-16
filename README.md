# The Evolving Cyber Threat Landscape: A Decade in Review

## Executive Risk Intelligence Report (2015-2024)

A professional R Quarto analysis project showcasing cybersecurity threat intelligence and risk visualization expertise.

---

## Project Overview

This project analyzes 10 years of global cybersecurity threat data (3,001 incidents) to provide executive-level insights on:

- Financial impact trends across industries and geographies
- Evolution of attack types and sophistication
- Defense mechanism effectiveness
- Incident response performance metrics
- Strategic recommendations for C-suite and Board members

- Note: A manifest.json file specifying R dependencies is required within the R project to publish on Posit CLoud
---

## Project Structure

```
cyber_threat_landscape/
├── cyber_threat_landscape.qmd      # Main Quarto document
├── custom_style.css                 # Professional CSS styling
├── Global_Cybersecurity_Threats_2015-2024.csv  # Data file
├── README.md                        # This file
├── setup_and_render.R              # Setup and rendering script
└── outputs/                         # Generated reports (created on first run)
```

---

## Prerequisites

### Required Software

1. **R** (version 4.0 or higher)
   - Download: https://cran.r-project.org/

2. **RStudio** (recommended but optional)
   - Download: https://posit.co/download/rstudio-desktop/

3. **Quarto CLI** (version 1.3 or higher)
   - Download: https://quarto.org/docs/get-started/

### Required R Packages

The following packages will be automatically installed by the setup script:

- `tidyverse` - Data manipulation and ggplot2 for visualization
- `plotly` - Interactive plots
- `scales` - Scale functions for ggplot2
- `patchwork` - Combining plots
- `gt` - Professional tables
- `RColorBrewer` - Color palettes
- `lubridate` - Date handling
- `gghighlight` - Highlighting in plots
- `ggridges` - Ridge plots
- `quarto` - Quarto rendering (if using R to render)

---

## Key Features

### Visualizations Included

1. **Financial Impact Analysis**
   - Annual loss trends with area charts
   - Incident frequency vs. average loss comparison
   
2. **Attack Type Evolution**
   - Time series of attack type trends
   - Proportional distribution analysis
   - Financial impact by attack type

3. **Industry Sector Analysis**
   - Financial loss heatmap (Industry × Year)
   - Industry vulnerability index with professional tables
   
4. **Geographic Threat Distribution**
   - Global risk matrix (bubble chart)
   - Top 10 countries by financial loss

5. **Attack Sophistication Index**
   - Vulnerability exploitation trends
   - Zero-day vs. traditional vulnerabilities
   - Attack source attribution analysis

6. **Incident Response Effectiveness**
   - Resolution time trends with confidence intervals
   - Defense mechanism performance comparison
   - Effectiveness scoring matrix

7. **2024 Emerging Trends**
   - Year-over-year change analysis
   - Critical threat alerts

### Interactive Features

- **Hover tooltips** on all charts showing detailed data
- **Zoomable plots** for detailed inspection
- **Clickable legends** to filter data series
- **Professional tables** with sorting and highlighting
- **Collapsible code sections** for technical readers

---

## Data Source & Methodology

**Dataset:** Global Cybersecurity Threat Database
- **Records:** 3,001 documented incidents
- **Time Period:** 2015-2024 (10 years)
- **Countries:** 12 major economies
- **Industries:** 7 key sectors
- **Metrics:** Financial loss, affected users, resolution time, attack attributes

**Analysis Approach:**
- Descriptive statistics
- Time series analysis
- Comparative trend analysis
- Risk scoring and indexing

**Limitations:**
- Represents reported incidents only
- Actual volumes likely higher due to underreporting
- Focus on major economies may not reflect global diversity

---





