Question 2: ADaM ADSL Dataset Creation

Objective

Create an ADaM Subject-Level Analysis Dataset (ADSL) from SDTM source data using the {admiral} package and tidyverse tools, with custom derivations for age grouping, treatment timing, ITT population flag, and last known alive date.

Overview

The ADSL (Subject-Level Analysis Dataset) is the foundation of ADaM datasets, containing one record per subject with demographic, treatment, and population flag information. This solution demonstrates advanced derivations including date/time imputation, population definition, and complex date calculations.