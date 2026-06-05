# ENVS-193DS_homework-03

Homework 3 from ENVS 193DS at UC Santa Barbara. This assignment covers correlation analysis using two datasets: one examining the relationship between ocean temperature and giant kelp frond elongation rate, and a personal dataset tracking focus level, work days, and water intake. The assignment also includes an affective visualization and a statistical critique.

---

## General Information

- **Course:** ENVS 193DS | Spring 2026 | UC Santa Barbara
- **Author:** Gabriela Davidson (GitHub: gdavidson533)
- **Rendered document:** [https://drive.google.com/file/d/1WOCL7btfbCaSP_k4cp64WB5yMnlt1icY/view?usp=drive_link]
- **Repository:** [https://github.com/gdavidson533/ENVS-193DS_homework-03.git]

---

## Data and File Information

### Repository Structure

ENVS-193DS_homework-03/

- data/
  - temp-kelp.csv — Kelp and temperature data (Problem 1)
  - MyData_Homework3.csv — Personal dataset (Problem 2)
- Homework_3.qmd — Main analysis document
- Homework_3.html — Rendered output
- README.md — This file

---

### Data Files

**`temp-kelp.csv`**
- **Source:** Provided by ENVS 193DS course instructors
- **Description:** Paired measurements of ocean temperature and giant kelp frond elongation rate from kelp forest monitoring sites
- **Variables:**
  - `temp_c` — Ocean temperature (°C)
  - `kelp_elong` — Giant kelp frond elongation rate (cm day⁻¹)

**`MyData_Homework3.csv`**
- **Source:** Personally collected per Homework 3 prompt
- **Description:** Personal observations tracking daily focus level, whether the day was a work day, and water intake
- **Variables:**
  - `date` — Date of observation
  - `focus_level` — Self-reported focus level (scale of 1–5)
  - `work_day` — Whether the day was a work day (yes/no)
  - `water_intake_L` — Water intake in liters (L)

---

## Packages Used

- `tidyverse` — data wrangling and visualization
- `here` — reproducible file paths
- `janitor` — cleaning column names