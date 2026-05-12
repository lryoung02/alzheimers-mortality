# Alzheimer's Mortality and Risk Factors in the U.S.
Modeling and mapping social determinants of health and mortality of Alzheimer's disease, a progressive neurological condition.

# Description
Alzheimer's is a degenerative neurological condition, affecting memory, language, and behavioral responses. There are both genetic (modifiable) factors and socioeconomic (non-modifiable) factors that may be contributing to increased risk of Alzheimer's. Assessing social determinants of health and disease rates are important to address health inequalities and lower prevelance. My project analyzed the mortality of Alzheimer's disease in the U.S. by state and assessed social determinants of health to determine potential risk factors and better understand populations most at risk.

# Analyses and Data
Data was obtained for the 2017 leading causes of death in the U.S. from the National Center for Health Statistics (NCHS). The NCHS data was filtered for Alzheimer's disease for each state and included age-adjusted death rate (per 100,000 population). U.S. Census Bureau data was also obtained from the American Community Survey (ACS) for the 2016 5-year estimates of age (% 65+), median income, education (% bachelor's degree or higher), health insurance (% uninsured), and poverty (% in poverty). The ACS data was converted to tidy format. The filtered NCHS data and ACS data were combined into one final dataset used for analysis.

Analysis was performed in RStudio with Version: 2026.04.0-526 using R packages, "tidyverse," "dplyr," "patchwork," "car," "ggplot2", "scales," "ggfortify," "plotly," "ggrepel," "lmtest," "htmlwidgets," "htmltools," "corrplot," and "broom."

All analysis is described in Final_Code.Rmd

# Authors
Lauren Young (@lryoung02)
