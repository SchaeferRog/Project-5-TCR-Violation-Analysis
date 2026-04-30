# TCR Violations Analysis
**CIVE 202 | Spring 2026 | Group ENVRN-02-14**

## Overview
This project analyzes Total Coliform Rule (TCR) violations across the United States on behalf of a research team at the University of Massachusetts Amherst. Using data from the EPA's Safe Drinking Water Information System (SDWIS), TCR violations are examined across five states — one from each EPA region — to identify where violations occur, why differences exist between regions, and how violation rates compare between small and large water systems.

---

## Methods
All analysis was completed in Python (Jupyter Notebook) using the following libraries:
- **pandas** — data manipulation and cleaning
- **matplotlib / seaborn** — static visualizations
- **plotly** — interactive time series plots

Raw SDWIS data was downloaded, cleaned, and compiled into a `.csv` file. One state per EPA region was selected for analysis. Violations were categorized by state, county, water system size (very small, small, medium, large, very large), and time period.

---

## Repository Contents
| File | Description |
|---|---|
| `ENVRN-02-14_Project5_PythonCode` | Jupyter Notebook with full analysis |
| `ENVRN-02-14_Project5_ACD` | Annotated Code Document |
| `ENVRN-02-14_Project5_Report` | Technical report and executive summary |
| `ENVRN-02-14_Project5_GanttChart` | Project timeline |
| `ENVRN-02-14_Project5_TimeSheet` | Team time log |

---

## Methodology Summary
1. **Data Collection** — Download and clean SDWIS violation records for five states across EPA regions
2. **Exploratory Analysis** — Organize violations by state and county; generate comparison plots using Seaborn
3. **System Size Analysis** — Categorize violations by water system size using EPA population-served definitions
4. **Time Series Analysis** — Build interactive Plotly plot showing active violations over time per state
5. **Documentation** — Compile findings into a written report and annotated code document
