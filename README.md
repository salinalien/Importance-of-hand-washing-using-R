# Importance-of-hand-washing-using-R
The analysis aims to reexamine the data that led Dr. Semmelweis to discover the importance of handwashing in reducing mortality rates among women giving birth at the Vienna General Hospital.

Analysis was performed in R using various libraries such as tidyverse for data manipulation and visualization

## Data Files:
yearly_deaths_by_clinic.csv: This CSV file contains yearly data on the number of women giving birth and the number of deaths at two clinics at the Vienna General Hospital between 1841 and 1846.
- Columns: year (Years 1841-1846), births (Number of births), deaths (Number of deaths), clinic (Clinic 1 or Clinic 2).

monthly_deaths.csv: This CSV file contains monthly data from 'Clinic 1' of the hospital, where most deaths occurred.
- Columns: date (Date in YYYY-MM-DD format), births (Number of births), deaths (Number of deaths).

## Analysis files
- notebook.ipynb: This Jupyter Notebook file contains the output of the R analysis script.

## Conclusion
Based on the reanalysis of Dr. Ignaz Semmelweis's data, the conclusion drawn is likely to reinforce the significance of handwashing in reducing mortality rates among women giving birth.

Results show:
- a decrease in the proportion of deaths after the introduction of handwashing on June 1st, 1847.
- a significant difference in the mean proportion of deaths before and after the implementation of handwashing
