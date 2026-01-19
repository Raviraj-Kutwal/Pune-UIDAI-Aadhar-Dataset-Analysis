# Pune-UIDAI-Aadhar-Dataset-Analysis

## Overview
This project analyzes the **UIDAI Aadhaar monthly enrolment , UIDAI demographic update , UIDAI biometric Update  datasets for Pune district** using Python.  
The notebook focuses on examining **Aadhaar enrolments, biometric updates, and demographic updates** across different age groups to understand how identity registrations and updates are distributed.

The work is purely exploratory and descriptive in nature.

---

## Dataset
- Source: UIDAI Aadhaar Monthly Enrollment Data ,  UIDAI demographic update , UIDAI biometric Update
- Region: Pune District


### Data includes:
- Aadhaar enrolments by age groups:
  - 0–5 years
  - 5–17 years
  - 18+ years
- Biometric updates:
  - Fingerprint updates
  - Iris updates
- Demographic updates:
  - Address updates
  - Name updates
  - Date of birth updates
  - Gender updates
  - Mobile and email updates

---

## Tools and Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## Work Done
1. Loaded the Aadhaar datasets using Pandas and inspected its structure.
2. Selected columns related to enrolments, biometric updates, and demographic updates.
3. Aggregated enrolment data across different age groups using column-wise summation.
4. Analyzed biometric update counts to observe relative distribution between fingerprint and iris updates.
5. Examined demographic update data to understand the frequency of different types of data modifications.
6. Used basic descriptive analysis to summarize observed patterns.
7. Created visualizations using Matplotlib and Seaborn to compare enrolment and update categories.

---

## Visualizations
The notebook includes:
- Bar plots for age-wise Aadhaar enrolments
- Comparison plots for biometric updates
- Distribution plots for demographic updates
- Combined plots to compare enrolments with update activities

---

## Observations
- Aadhaar enrolments are highest in the adult (18+) category.
- Biometric updates are consistently present across age groups.
- Demographic updates such as address and contact details form a significant portion of update activity.
- The dataset reflects Aadhaar activity beyond initial enrolment, including ongoing data updates.

---

## Files
- `Untitled15.ipynb` – Jupyter notebook containing data analysis and visualizations

---

## Notes
This project is intended as an exploratory analysis of publicly available Aadhaar statistics and does not involve predictive modeling or inference.

