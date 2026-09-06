# HealthConnect Clinic — Week 5 Data Analytics

## Project Overview

This notebook continues the HealthConnect Clinic analysis developed during Week 4. The objective is to explore appointment attendance and no-show behaviour, evaluate the previously defined KPIs, identify actionable business insights, and formulate recommendations.

## Data Preparation

The Week 4 processed dataset was used as the starting point for Week 5.

Key data-quality tasks included:

* Missing-value identification and treatment.
* `Reminder Channel` missing values were interpreted as `No Reminder` based on the established business meaning of the data.
* Numerical missing values were handled after examining their distributions.
* Duplicate and data-quality checks were performed before analysis.

## Exploratory Data Analysis

The analysis explored relationships between appointment outcomes and:

* Appointment type
* Reminder status and reminder channel
* Previous no-show history
* Distance to clinic
* Waiting time
* Numerical variables and their correlations

## KPIs

Four KPIs defined during the previous stage were calculated and evaluated:

1. **Attendance Rate**
2. **No-Show Rate**
3. **Reminder Effectiveness**
4. **Attendance Rate by Reminder Channel**

The KPIs were selected to measure appointment attendance, quantify the no-show problem, and evaluate reminder-related patterns.

## Key Results

The analysis found that no-shows represented **48.46%** of appointments, compared with **46.28% attended** and **5.26% cancelled**.

The strongest observed patterns involved previous no-show history, reminder behaviour, and appointment type. Distance to clinic and waiting time did not show meaningful relationships with no-show behaviour in the analysed data.

## Business Recommendations

Recommendations focus on:

* Targeting patients with repeated previous no-shows.
* Improving reminder coverage.
* Monitoring reminder-channel performance.
* Investigating follow-up appointments as a higher-risk appointment type.
* Avoiding unsupported assumptions about distance and waiting time as primary drivers of no-shows.

## Limitations

The findings represent exploratory associations and do not establish causation. The analysis is also limited to the variables available in the dataset, and imputation of missing numerical values introduces some uncertainty. Further validation and advanced analysis are required before implementing interventions at scale.
