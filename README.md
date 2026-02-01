# Women as Policymakers: Analyzing Gender-Based Quotas in Leadership
This repository contains an analysis of the Women as Policymakers dataset, exploring the impact of leadership quotas for women in Indian village councils on the provision of public goods. The study is based on Chattopadhyay and Duflo's (2004) influential research and leverages a randomized policy experiment to establish causal relationships.

## Project Overview
The analysis aims to:
* Quantify the effect of gender-based quotas on the provision of public goods such as drinking water and irrigation facilities.
* Evaluate the effectiveness of randomization in achieving balanced covariates between treatment and control groups.
* Compare treatment effects using both regression modeling and mean difference approaches.

## Dataset Description
The dataset focuses on the Birbhum district in West Bengal, India, and includes 322 observations with the following variables:
* GP: Village council identifier.
* Village: Location identifier.
* Reserved: Treatment indicator for gender-based leadership quotas.
* Female: Indicator for female leadership, independent of quotas.
* Water: Number of new or repaired drinking water facilities.
* Irrigation: Number of new or repaired irrigation facilities.

The data originates from supplementary materials in Imai’s Quantitative Social Science: An Introduction (2017).

## Key Insights
### Effectiveness of Women Leaders:
* Villages with quotas for women leaders showed an increase of 9.25 new or repaired drinking water facilities, a statistically significant improvement.
* Irrigation facilities decreased by 0.37 in such villages, though this result was not statistically significant.

### Randomization and Covariates:
Randomization effectively balanced observed and unobserved covariates between treatment and control groups. However, incorporating additional controls like income and education levels could enhance statistical precision.

The treatment effect was assessed using both mean differences and regression coefficients, leveraging the randomized experimental design to ensure unbiased causal estimates.

## Getting Started
1. Clone this repository:
git clone https://github.com/username/Women-Policymakers-Analysis.git
2. Open the RMarkdown file Women_Policymakers_Analysis.Rmd in RStudio.
3. Knit the file to generate the report in HTML, PDF, or Word format.

## Prerequisites
To replicate the analysis, ensure you have the following:
* R (version 4.0 or higher)
* RStudio
* Required R packages:
  * tidyverse
  * ggplot2
  * dplyr
  * knitr
  * rmarkdown

Install all required packages using:
install.packages(c("tidyverse", "ggplot2", "dplyr", "knitr", "rmarkdown"))

## References
Chattopadhyay, R., & Duflo, E. (2004). Women as policymakers: Evidence from a randomized policy experiment in India. Econometrica, 72(5), 1409–1443. doi:10.1111/j.1468-0262.2004.00539.x

Imai, K. (2017). Quantitative social science: An introduction. Princeton: Princeton University Press.

## Author
Julieta Pappano  
_Policy and Innovation Specialist_
