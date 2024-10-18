# 1.0 Title
Exploratory Data Analysis of Female Breast Cancer Patients diagnosed between 2006 & 2010: SEER BREAST CANCER DATA
(Pydata_Capstone_Project)

# 1.1 Project description
Analysis of the data to get trends & insights on survival of female breast cancer patients from diagnosis (2006 – 2010) until time of follow up, specifically:

Entails the following:
1. Univariate analysis of all data columns/variables.
2. Bivariate analysis of patient demographic variables.
3. Bivariate analysis of patient demographic variables and the categorical variables describing the cancer stage, tumour characteristics and hormone receptor status.
4. Bivariate analysis of categorical variables describing the cancer stage, tumour characteristics and hormone receptor status and survival months.
5. Bivariate analysis of categorical variables describing the cancer stage, tumour characteristics and hormone.receptor status and status on follow up.
6. Bivariate analysis of the patient demographic variables and survival months.
7. Bivariate analysis of the patient demographic variables and status on follow up.
8. Bivariate analysis of all numerical variables and survival months.
9. Bivariate analysis of all numerical variables and status in months.


# 1.2 Description of dataset
Data obtained from https://ieee-dataport.org/open-access/seer-breast-cancer-data

This dataset of breast cancer patients was obtained from the **2017 November update** of the SEER Program of the NCI, which provides information on population-based cancer statistics. 

The dataset involved female patients with infiltrating duct and lobular carcinoma breast cancer (SEER primary cites recode NOS histology codes 8522/3) **diagnosed in 2006-2010.**

Patients with unknown tumour size, examined regional LNs, positive regional LNs, and patients whose survival months were less than 1 month were excluded; thus, 4024 patients were ultimately included.

The columns in the dataset provide details about the patients' demographics, cancer stage, tumor characteristics, lymph node examination results, hormone receptor status, survival months and survival status.

Key features:

**PATIENT DEMOGRAPHIC VARIABLE**S

**Age:** Age of the patient.

**Race:** Ethnicity of the patient.

**Marital Status:** Marital status at diagnosis.

**DISEASE VARIABLES**
1. **CANCER STAGE**

**T Stage:** Tumor size classification.

**N Stage:** Regional lymph node involvement.

**6th Stage:** Overall cancer stage based on the 6th edition of the AJCC Cancer Staging Manual.

2. **TUMOUR CHARACTERISTICS**
**Grade** Aggressiveness of cancer/how cells differe from the normal breast tissue cell

**A Stage:** Anatomical stage of cancer.

**Tumor Size:** Size of the tumor.
 
3. **HORMONAL STATUS**

**Estrogen Status:** Estrogen receptor status (positive or negative).

**Progesterone Status:** Progesterone receptor status (positive or negative).

4. **LYMPH NODE EXAMINATION**

**Regional Node Examined:** Number of lymph nodes examined.

**Regional Node Positive:** Number of lymph nodes that tested positive.

**PATIENT OUTCOME VARIABLES**

**Survival Months:** Number of months the patient survived.

**Status:** Whether the patient was alive or dead at the time of follow-up.

# 1.3 Installation
## Installation of the packages
pip install numpy
pip install pandas

## Importation of the required modules
import numpy as np
import pandas as pd
import datetime as dt
import csv
import matplotlib
import matplotlib.pyplot as plt
import seaborn as sns

# 1.4 Usage

See code and findings in breastcancerdata.ipynb notebook

# 1.5 Acknowledgements/Attributions
1. IEEE DATAPORT - https://ieee-dataport.org/open-access/seer-breast-cancer-data
