# TED Talk Popularity Analysis

This repository contains an analysis project that investigates the factors predicting the popularity of TED Talks. The project uses data scraped from the official TED website and applies inferential techniques along with modeling approaches to understand which attributes contribute to a talk's success.

## Overview

- **Objective:**  
  Determine the key characteristics—such as talk duration, language availability, speaker count, and thematic tags—that influence the popularity of TED Talks.

- **Approach:**  
  - **Data Cleaning & Preprocessing:**  
    Remove incomplete records, convert timestamps, process tags, and normalize rating data.
  - **Exploratory Data Analysis (EDA):**  
    Use descriptive statistics and visualizations (e.g., pairs plots, box plots) to examine variable distributions and correlations.
  - **Modeling:**  
    Apply linear regression with polynomial and interaction terms, and use stepwise AIC for model selection.
  - **Diagnostics:**  
    Validate the model using residual analysis, outlier detection, and influence diagnostics.

## File Structure

```plaintext
TED-Talk-Popularity-Analysis/
├── TED_Popularity_Analysis.pdf    # Main report with methodology, analysis, and conclusions.
├── R_code_Appendix.pdf            # R code for data cleaning, EDA, modeling, and diagnostics.
├── TEDTalkDescription.pdf         # Description of the project, dataset details, and research questions.
└── (Additional files, e.g., raw data or supplementary materials)

## How to Run the Analysis

### Requirements
- **R:** Version 3.6 or higher.
- **R Packages:** `readr`, `dplyr`, `tidyverse`, `ggplot2`, `GGally`, `lmtest`, `olsrr`, `patchwork`  
  *(Install these packages if not already available.)*

### Instructions
1. Clone or download this repository.
2. Open the `R_code_Appendix.pdf` file to review the R scripts used for data cleaning, EDA, modeling, and diagnostics.
3. Ensure that the TED Talks dataset (if not already included) is in the correct directory.
4. Run the R scripts in your preferred R environment (e.g., RStudio) to replicate the analysis.

## Dataset Description

After cleaning, the dataset covers TED Talks data from 2006 to September 21, 2017 and includes the following variables:

- **Comments:** Number of first-level comments.
- **Duration:** Duration of the talk in seconds.
- **Languages:** Number of languages in which the talk is available.
- **Num_speaker:** Number of speakers featured in the talk.
- **Published_date & Film_date:** Timestamps for publication and filming.
- **Ratings:** A dictionary of ratings and their frequencies.
- **Tags:** Themes or topics associated with each talk.
- **Views:** Total number of views for the talk.

## Authors

- **Langxin Li**
- **Derrick Li**
- **Qi Sun**
- **Yangxinyue Wang**

## Acknowledgements

This project was developed as part of the STAC 67 report. We extend our gratitude to our team members, the TED organization, and the academic references that informed our analysis.
