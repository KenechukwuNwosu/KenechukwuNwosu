# Kenechukwu O. S. Nwosu, MBBS, MPH

### Physician-Epidemiologist | Real-World Evidence & Health Outcomes Research | Observational Health Data Analytics

I am a physician-epidemiologist and PhD candidate in Epidemiology at UTHealth Houston, specializing in real-world evidence, health outcomes research, and observational health data analytics. I use epidemiologic design and reproducible computational methods to transform claims, EHR, survey, clinical, and population health data into evidence for healthcare and research decision-making.

My portfolio demonstrates SAS-based claims cohort construction, leakage-aware biomedical machine learning in R, survey-weighted epidemiology, cancer outcomes research, program evaluation, and research informatics.


## Research & Professional Interests

- **Real-World Evidence & Health Outcomes Research** — observational health data, healthcare utilization, outcomes, disparities, and evidence generation
- **Epidemiology & Population Health** — observational research, disease surveillance, health disparities, and population-level risk factors
- **Oncology & Cancer Outcomes Research** — cancer disparities, treatment patterns, healthcare access and utilization, survival outcomes, and population-based cancer research
- **Program Evaluation & Implementation** — evaluation frameworks, KPIs, mixed methods, implementation barriers, cost and ROI analysis
- **Clinical & Translational Research** — clinical research processes, human-subjects research, and translation of clinical and population data into actionable evidence
- **Infectious Diseases & Global Health** — outbreak response, surveillance, community interventions, and infectious-disease research
- **Data Science for Health Research** — statistical programming, predictive modeling, reproducible analytics, geospatial analysis, and research visualization


## Technical Toolkit

**Real-World Evidence & Cohort Analytics**
SAS • SQL • Administrative Claims • EHR • Cohort Construction • Claims-Based Phenotyping • Healthcare Utilization • Cost & ROI Analysis

**Epidemiologic & Outcomes Research**
Observational Study Design • Regression Analysis • Survey-Weighted Analysis • Disease Surveillance • Program Evaluation • Health Outcomes Analysis

**Predictive Modeling & Reproducible Research**
R • tidyverse • tidymodels • Machine Learning • Grouped Cross-Validation • Model Validation • Reproducible Analytical Workflows

**Research Data, Programming & Communication**
Stata • Python/pandas • Excel • SQLite • SEER • BRFSS • HINTS • MEPS • NSCH • Biopython/PubMed • Plotly • Research Dashboards

**GIS & Mixed Methods**
ArcGIS • NVivo • Geospatial Analysis • Thematic Analysis • Codebook Development • Data Visualization


## Featured Research & Projects

### 🏥 [Claims to Cohorts](https://github.com/KenechukwuNwosu/claims-to-cohorts)
**From Administrative Healthcare Data to Reproducible Analytic Cohorts in SAS**

Built a reproducible **SAS healthcare claims analytics framework** using six complementary datasets spanning 1.8+ million enrollment, inpatient, professional, pharmacy, and hospital-discharge records. Transformed raw administrative data into analysis-ready cohorts across multiple clinical and health-services use cases while preserving transparent eligibility, denominator, coding, and data-governance logic.

**Methods:** Cohort Construction • Claims-Based Phenotyping • Person-Time Denominators • Healthcare Utilization • Medication Exposure • Resource-Use Analysis • ICD-9/ICD-10 Portability  
**Tools:** SAS • PROC SQL • DATA Step • ODS Graphics  
**Data:** CMS DE-SynPUF • Pharmacy Claims • Texas THCIC Inpatient & Facility Data

**Biopharma Relevance:** Demonstrates foundational real-world data methods for defining observable populations, constructing clinical phenotypes, characterizing medication exposure, and measuring healthcare utilization and resource use.

[View the full Claims to Cohorts repository](https://github.com/KenechukwuNwosu/claims-to-cohorts)

---

### 🎙️ [VoiceMark PD](https://github.com/KenechukwuNwosu/voicemark-pd)
**Leakage-Aware Machine Learning for Parkinson's Classification from Acoustic Voice Biomarkers**

Rebuilt a Parkinson's disease classification workflow in **R/tidymodels** using repeated voice recordings from 252 participants. Implemented participant-grouped train/test splitting and repeated grouped cross-validation to prevent repeated-measures leakage, then compared six machine-learning classifiers under a common validation framework.

**Methods:** Machine Learning • Grouped Cross-Validation • Predictive Modeling • Model Validation • Permutation Importance  
**Tools:** R • tidymodels • DALEX  
**Data:** UCI Parkinson's Disease Classification Dataset

**Biopharma Relevance:** Demonstrates how validation design can alter apparent biomedical model performance and why participant independence matters when evaluating evidence generated from repeated clinical measurements.

[View the full VoiceMark PD repository](https://github.com/KenechukwuNwosu/voicemark-pd)
