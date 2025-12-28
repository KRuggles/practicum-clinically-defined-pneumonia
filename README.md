# EMR Surveillance of Hospital-Acquired Pneumonia: Leveraging the NHSN Clinical Definition of Pneumonia

## Hospital‑Acquired Pneumonia (HAP) Risk Prediction Model
This repository contains the full analysis, code, and documentation for my Master of Public Health practicum project, which examines system‑wide HAP incidence and develops a preliminary logistic regression model to identify patients at elevated risk.

## Background
Hospital‑acquired pneumonia (HAP) is a preventable complication associated with significant morbidity, mortality, and cost. Despite its impact, HAP surveillance is challenging due to inconsistent documentation and the complexity of diagnosis. This project uses multi‑year EMR data and natural language processing (NLP) to build a reproducible, system‑wide risk prediction model that can support early identification and prevention efforts.

## Files
Grafton clinically-defined HAP practicum.pdf - the document turned in for practicum
cxr_nlp.nb - natural language processing of chest x-rays (all data needed is contained within the file)
practicum analysis.nb - contains data analysis and build of logistic regression model (all data needed is contained within the file) 

*Note: the .nb files need Wolfram Mathematica to run. If you do not have the software, a free reader allowing you to access the files can be downloaded [here](https://www.wolfram.com/player/).*

## Methods Overview
- Data source: Three years of system‑wide EMR data from 13 hospitals
- Outcome definition: NHSN clinically defined pneumonia criteria, including NLP‑based classification of chest x‑ray impressions
- Predictors: Patient‑level demographics, encounter variables, comorbidities, clinical factors, and hospital characteristics
- Modeling approach: Logistic regression with variable selection based on statistical significance and clinical relevance
- Reproducibility: All code and used for data processing and modeling is included in this repository

## Key Findings
- HAP incidence varies meaningfully across the Hospital System.
- Several patient‑level and encounter-level factors are strongly associated with increased risk.
- The NLP classifier enables scalable use of free‑text imaging data.
- The final regression model demonstrates strong internal validity and clinical relevance.

## Future Directions
The results support advancing this model toward prospective evaluation. Additional refinement — including testing new variables (e.g., Social Vulnerability Index, collapsed hospital‑type categories) and incorporating clinician feedback — will strengthen readiness for a randomized clinical trial of the HAP risk score.

## Reproducibility
All code used in this project is included to support transparency and reproducibility. Data has been de-identified due to patient privacy restrictions.

## Feedback? 
I welcome any constructive criticism, as the project is ongoing and I am always looking to improve.
