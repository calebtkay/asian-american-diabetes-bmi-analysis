---
output:
  pdf_document: default
  html_document: default
---
```{r}
# Data Dictionary

| Variable | Source file | Plain-English meaning | Notes |
|---|---|---|---|
| SEQN | all files | Respondent ID | Used to merge the 5 files together |
| RIDRETH3 | demographic.csv | Race/ethnicity | Code 6 = Non-Hispanic Asian (per CDC codebook) |
| RIDAGEYR | demographic.csv | Age in years | |
| BMXBMI | examination.csv | Body Mass Index | |
| LBXGH | labs.csv | HbA1c (%) | Only measured on a lab subsample, not everyone |
| DIQ010 | questionnaire.csv | Self-reported diabetes diagnosis | 1 = Yes, 2 = No, 3 = Borderline |
```


