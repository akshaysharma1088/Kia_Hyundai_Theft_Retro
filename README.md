# Kia_Hyundai_Theft_Retro
The following analysis uses publicly available data to examine the sharp increase in Kia and Hyundai vehicle thefts across the United States. This story is aimed at local policymakers, public safety officials, and journalists.

# Project Overview

This project analyzes the surge in Kia and Hyundai vehicle thefts across the United States using publicly available datasets. The goal is to uncover temporal, geographic, and behavioral patterns in theft incidents and inform public policy discussions.

# Objectives

Quantify the rise in theft incidents over time.

Identify hotspots and geographic trends in theft rates.

Examine demographic and vehicle characteristics that may influence risk.

Provide actionable insights for policymakers and law enforcement.

# Tools & Technologies

Language: R

Libraries: tidyverse, ggplot2, dplyr, lubridate, readr

Environment: RStudio

# Data Description

Publicly available vehicle theft incident data (police reports, open data portals, NHTSA datasets).

Timeframe covers multiple years of theft data across major U.S. cities and states.

# Methodology

Data Cleaning & Transformation – Standardized columns, cleaned location fields, and handled missing values.

Exploratory Analysis – Examined theft counts by year, make, model, and location.

Visualization – Used ggplot2 to create time-series plots, bar charts, and geographic maps.

Storytelling – Structured analysis as a narrative aimed at policymakers and the public.

Policy Angle – Highlighted vulnerabilities in older Kia/Hyundai models lacking immobilizers.

# Key Insights

Theft incidents spiked dramatically after 2021, coinciding with social media trends.

Hotspots were concentrated in urban centers in the Midwest and coastal states.

Older Kia/Hyundai models are disproportionately targeted due to security design gaps.

# How to Run
# Clone the repo
git clone https://github.com/akshaysharma1088/Kia_Hyundai_Theft_Retro.git
cd Kia_Hyundai_Theft_Retro

# Open the R project in RStudio and run analysis scripts
Rscript analysis/theft_analysis.R
