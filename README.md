# ADA-Final-Case
# Comparative Evaluation of Training Programs Using Experimental Design

This project assesses the effectiveness of three employee training programs—Program A, Program B, and the Current Program—across six regional offices at NLS. The goal was to determine which program led to the most improvement in employee application and proficiency scores.

## 📊 Objective
Evaluate training impact using experimental design and regression analysis to:
- Measure employee improvement pre- and post-training
- Isolate the effect of each program using Difference-in-Differences modeling

## 🧪 Experimental Design

| Group         | Program         | Offices              |
|---------------|------------------|-----------------------|
| Control       | Current Program  | New York, Los Angeles |
| Treatment A   | Program A        | Miami, Houston        |
| Treatment B   | Program B        | Detroit, Denver       |

## 📈 Analysis Overview

- Calculated improvement in **proficiency** and **application** scores
- Created dummy variables to encode program groups
- Applied **OLS regression** to evaluate score improvements across training groups
- Used a Difference-in-Differences
