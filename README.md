# Volts Analysis with Transformation
# Overview: 
This project analyzes the **Volts** dataset in R, using simple linear regression to examine the relationship between Voltage and time. An initial regression was fit to the raw data. However after diagnostic checks were completed, the assumptions of simple linear regression were not well satisfied. Thus, to remedy the issue, a logarithmic transformation was applied to the response variable (Volts) to improve the model fit and validity of the SLR assumptions.
# Content:
1. Volts_Statistical_Report.pdf -Discussion of findings 
2. Volts_Source_Code.Rmd - Source code for reproducibility and/or modification
3. Volts_Statistical_Analysis.pdf - Knitted file containing R code and data visualization
# Requirements:
1. R must be version 4.0 or greater
2. R packages required for analysis - ggplot, dyplyr, Stat2Data (source for Volts dataset)
# Analysis Overview:
1.	Examine the direction, strength and relationship between variables for the original data
2.	Check linearity, constant variance and normality of data for the original scatterplot
3.	Examine direction, strength and relationship between variables for the transformed data
4.	Check linearity, constant variance, and normality of data for the transformed data
5.	Determine if the transformed data is more suitable for a simple linear regression model
6.	Identify any outliers and or influential points on the transformed data
7.	Model limitations of the log transformed data
# Key Findings:

# Contributions:
This repository was created as part of my statistical analysis portfolio. Suggestions for extending the analysis (other transformations like the inverse, square root, exponential) are welcome. 
