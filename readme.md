# Medical Statistical Analysis Project

## Overview
This project performs statistical analyses on medical data using R, focusing on:
- Diagnostic test evaluation
- IQ score distribution analysis
- Poisson distribution of asthma attacks
- Binomial distribution analysis of myocardial infarction rates

## Analysis Components

### 1. Diagnostic Test Evaluation
- Analyzes sensitivity and specificity of a noninvasive test compared to standard angiogram
- Computes positive predictive value with 20% stroke prevalence
- Includes visualization using mosaic plots

### 2. Stanford Binet IQ Analysis
- Calculates Mensa membership cutoff score (98th percentile)
- Mean = 100, SD = 16
- Includes normal distribution visualization

### 3. Emergency Asthma Cases
- Models violent asthma attacks using Poisson distribution
- Calculates probability of 5+ cases over 2-day period
- λ = 2 cases per day

### 4. Myocardial Infarction Study
- Analyzes MI rates in postmenopausal women
- Uses binomial distribution (n=1000, p=0.01)
- Evaluates significance of observed events

## Requirements
- R (latest version recommended)
- Required R packages:
  - stats
  - graphics
  - base

## Usage
Open the R Markdown file (.Rmd) in RStudio and either:
1. Run individual chunks using the "Run" button
2. Knit the entire document using the "Knit" button

## Results
The analysis provides:
- Diagnostic test metrics (sensitivity: 0.9143, specificity: 0.7241)
- Mensa IQ cutoff score (~130)
- Probability calculations for rare medical events
- Statistical significance testing for observed outcomes

## Author
Casey Stockstill

## Date
February 24, 2025