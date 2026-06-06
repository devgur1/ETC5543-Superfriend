# ETC5543 SuperFriend Internship Project

This repository contains the final report and presentation for the ETC5543 Business Analytics Creative Activity project with SuperFriend.

## Project title

**Analysis of Financial and Psychological Distress in the Australian Workforce**

## Project overview

This project develops a repeatable workflow for analysing SuperFriend's Indicators of a Thriving Workplace (ITW) survey waves from 2024 and 2025.

The analysis examines psychological distress, burnout, workplace domains, psychosocial hazard management, financial distress, age groups, occupation type, ABS Living Cost Index context and RBA cash-rate context.

The report is structured around three applied questions:

1. When does workforce wellbeing risk appear to increase?
2. Who appears to be more affected?
3. What workplace and economic context helps contextualise the observed patterns?

## Final outputs

- `Report.qmd` — source file for the final report
- `Report.pdf` — final report PDF
- `Presentation.qmd` — source file for the final presentation
- `Presentation.html` — final presentation output

## Repository structure

The main files in this repository are:

- `Report.qmd`
- `Report.pdf`
- `Presentation.qmd`
- `Presentation.html`
- `README.md`
- `.gitignore`
- `Superfriend.Rproj`
- `data/README.md`

## Data availability

Raw ITW survey data is not included in this public repository because it contains confidential survey responses.

To reproduce the analysis in an approved environment, place the required ITW survey files and approved external economic indicator files in the `data/` folder using the filenames expected by `Report.qmd`.

Expected private data files include:

- `ITW_2024.sav`
- `ITW_2025.sav`
- `allgroupsbyhouseholds.xlsx`

These files are ignored by Git and should not be uploaded publicly.

## Reproducibility

The final report was prepared using R and Quarto. The main R packages used include tidyverse, haven, janitor, readxl, lubridate, broom, knitr and kableExtra.

To render the report:

`quarto render Report.qmd --to pdf`

To render the presentation:

`quarto render Presentation.qmd`

## Generative AI acknowledgement

Generative AI tools were used to support report structure, wording, editing and communication. All analysis decisions, code review, interpretation and final content responsibility remain my own. No confidential raw data was entered into generative AI tools.