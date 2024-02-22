# MARKUPEX
Endogenous pricing markups distribution and pecuniary externality of credit on monetary exchange

# Empirical Part for MARKUPEX

## Overview
This documentation covers the empirical analysis conducted for the study of the relationship between credit and markup (and its dispersion) in the United States from 1980Q1 to 2007Q4. The analysis utilizes Stata for generating tables and figures as per the findings discussed in our paper.

## Data Description
- `data.dta`: Contains the dataset used for the empirical analysis spanning from 1980 to 2007 in the United States.
- The variables used and their sources are detailed in Appendix C "Data and Measurement" of our paper.

## Code Structure
The empirical analysis is supported by four Stata `.do` files, each serving a unique purpose in the generation of tables and figures as outlined in the paper:

### 1. `Table 1, 4, 5, and 6.do`
This script conducts the empirical analysis on the relationship between credit and markup (and its dispersion). The tables are outputted in LaTeX format. It generates:
- "Table 1 OLS results: Markup and dispersion" in Section 4.2 Empirical evidence
- "Tables 4, 5, and 6" in Appendix D Robustness
  
### 2. `Table 3.do`
Generates "Table 3: Data sources and summary statistics" in Appendix C "Data and Measurement", providing an overview of the data utilized in our analysis.

### 3. `Figure 6.do`
Produces Figure 6: Time series of credit-to-GDP ratio and markup statistics for Section 4.2 Empirical evidence. It creates three figures illustrating:
  - (a) Credit and average markup
  - (b) Credit and markups dispersion
  - (c) Average markup and the effective Federal Funds rate

### 4. `Appendix VECM_Equation_D2_D3.do`
Outputs the VECM results discussed in Appendix D Robustness, examining the relationships involving:
  1. log of markup, log of real GDP, consumer credit-to-GDP, and log of real exchange rate
  2. markup dispersion, log of real GDP, consumer credit-to-GDP, and log of real exchange rate
Focuses on Equation D.2 and D.3.

## Prerequisites
- Stata: Required to run `.do` files for analysis.

## Usage
To run any of the `.do` files, navigate to the directory containing the files and execute the following command in Stata:
