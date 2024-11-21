# Exploratory Data Analysis Coursework: Digital Assignment - 1

[//]: # "--- Use 3 dashes for linebreak"

## Migraine Treatment Analysis

This project develops a model to analyze the Kostecki Dillon dataset, which contains information from a study on migraine treatments. The dataset, part of the carData package in R, documents records for patients undergoing bio-feedback treatments to reduce migraine occurrences.

### Dataset

The data were collected by Tammy Kostecki-Dillon and involve 133 patients who participated in a bio-feedback program aimed at reducing the frequency and severity of migraines.

[Dataset Documentation](https://rdrr.io/cran/carData/man/KosteckiDillon.html)

**Key Variables:**

- `id`: Patient identifier.
- `time`: Days relative to the onset of treatment (treatment begins at day 0).
- `dos`: Days from the start of the study (January 1 of the first year).
- `hatype`: Type of migraine experienced (`Aura`, `Mixed`, or `No Aura`).
- `age`: Age of the patient at the onset of treatment.
- `airq`: Measure of air quality.
- `medication`: Medication status (`none`, `reduced`, or `continuing`).
- `headache`: Presence of a headache (`no` or `yes`).
- `sex`: Gender of the patient (`female` or `male`).

**Study Details:**

Patients maintained headache logs during the treatment program, which spanned approximately three years. They were encouraged to record their experiences starting four weeks before treatment and continuing for one month afterward. However, only 55 patients provided data preceding the onset of treatment.

**Objectives Achieved**

Exploratory Data Analysis with the Kostecki-Dillon dataset
Loaded the dataset, explored its dimensions, summary, and performed data handling, data cleaning, univariate, bivariate and multivariate analysis. Completed all the tasks in parallel alignment to the theory sessions from module 2 to 7.
