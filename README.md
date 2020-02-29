# Improving Quality of Life Challenge and Data
## Launch Notebook
|          Platform         |                                                              Click Button To Launch                                                              |
|:-------------------------:|:------------------------------------------------------------------------------------------------------------------------------------------------:|
|        Google Colab       | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aihack20/nhs_challenge) |
| Standard Jupyter Notebook |                   [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/aihack20/nhs_challenge/master)                  |
## Problem Statement 
## Improving Quality of Life:

In 50 years’ time, it is projected that there will be an additional 8.2 million people aged 65 years and over in the UK – a population comparable to that of present-day London. In terms of proportions, the Office for National Statistics (ONS) projects that more than 24% of people living in the UK will be aged 65 or older by 2042, up from 18% in 2016. At the same time, life expectancy increases: In 2043 in the UK, 20.8% of newborn boys and 26.1% of newborn girls are expected to live to at least 100 years of age, an increase from 13.6% for boys and 18.2% for girls born in 2018.

What is the next step? As life expectancy increases, it is crucial to improve the quality of life among the elderly. As people age, they are more prone to having health issues and degenerative diseases such as cancer, dementia, infections due to viruses and bacteria. Osteoporosis and arthritis affecting the bones and joints, neurodegenerative diseases such as Alzheimer’s and Parkinson's, cancer, and diabetes are among the most common degenerative disease. 

Declining health associated with old age is often unavoidable but preventative measures can be taken to mitigate or delay the effects. Avoiding unhealthy habits such as smoking and drinking excessive amounts of alcohol as well as doing plenty of exercise and having a healthy diet are among the many things that one can do to improve life quality in old age. The NHS also carries out crucial preventative action in the form of promoting the above lifestyle choices as well as conducting screenings for degenerative diseases and providing health guidance for the elderly. These actions help reduce the number of patients that need to be admitted for primary or secondary care, not only improving their quality of life but also reducing the load on the NHS saving cost and enabling better care for everyone.

In this challenge, you will get the opportunity to help NHS prepare for the ageing population in the next 20 years.

You are asked to pose your own question along with the guidelines and answer it using the available datasets in the available time​. **What is important is the insightfulness and depth of your conclusions and analysis. ​You need not be comprehensive; quality data analysis is more important over the breadth of the question posed.**

Submissions may be predictive, using machine learning and/or time series analysis to predict or model rental trends. Submissions may also be illuminating, through the use of thoughtfully chosen data visualizations or sound statistical tests. Consider exploring the guiding questions below, or create your own variation. Creativity in formulating your own questions is encouraged; ​**however, it should not be at the expense of analytical depth, precision, and rigour, which are far more important.**

You may also use alternative datasets such as the ones on [data.gov.uk](http://data.gov.uk/) or [ons.gov.uk](http://ons.gov.uk/) The challenge will be assessed based on the accuracy, and technical soundness and appropriateness of the analysis as well as the value and novelty of the insights provided.

The following questions are provided as a guideline but they don't need to be followed exactly:

1. What is the effect of alcohol and tobacco consumption as well as increased pollution levels on dementia? Can you forecast the diagnosed dementia cases across the UK?
2. What are the biggest contributors to the decrease in quality of life among the elderly population?
3. What preventative action would you consider to counteract these? Is the NHS "Stop Smoking" campaign effective as a part of preventative actions?

## Datasets

The provided datasets are spread across six tables. Your team should only use the tables that
are relevant to your chosen question/topic. **You must use at least 1 of the listed datasets.**

### Prescription dataset

This API provides access to prescription data for each month over the past five years at GP practice and Clinical Commissioning Group level. A corresponding table connecting BNF codes to prescription sections are provided. This dataset can be used as a proxy to the incidence of various diseases and conditions such as Dementia or Nicotine dependence.

API access: [https://openprescribing.net/api/](https://openprescribing.net/api/)

BNF section stems for disease types:
### Datasets concerning lifestyle choices

Trends in alcohol and tobacco consumption:

CDID of Alcohol: ADIT

CDID of Tobacco Products: ZWUO

CDID of individual household consumption: ABJQ

[https://www.ons.gov.uk/economy/nationalaccounts/satelliteaccounts/datasets/consumertrends](https://www.ons.gov.uk/economy/nationalaccounts/satelliteaccounts/datasets/consumertrends)

Statistics on NHS Stop Smoking Services Campaign:

[https://digital.nhs.uk/data-and-information/publications/statistical/statistics-on-nhs-stop-smoking-services-in-england](https://digital.nhs.uk/data-and-information/publications/statistical/statistics-on-nhs-stop-smoking-services-in-england)

### General Datasets

GP Workforce:
[https://digital.nhs.uk/data-and-information/publications/statistical/general-and-personal-medical-services/final-31-december-2019](https://digital.nhs.uk/data-and-information/publications/statistical/general-and-personal-medical-services/final-31-december-2019)

GP Quality:

[https://digital.nhs.uk/data-and-information/publications/statistical/quality-and-outcomes-framework-achievement-prevalence-and-exceptions-data/2017-18](https://digital.nhs.uk/data-and-information/publications/statistical/quality-and-outcomes-framework-achievement-prevalence-and-exceptions-data/2017-18)

Patient Reported Outcome Measures:

[https://digital.nhs.uk/data-and-information/data-tools-and-services/data-services/patient-reported-outcome-measures-proms/guide-to-patient-reported-outcome-measures-proms](https://digital.nhs.uk/data-and-information/data-tools-and-services/data-services/patient-reported-outcome-measures-proms/guide-to-patient-reported-outcome-measures-proms)

Patient Registration:

[https://digital.nhs.uk/data-and-information/publications/statistical/patients-registered-at-a-gp-practice/january-2019](https://digital.nhs.uk/data-and-information/publications/statistical/patients-registered-at-a-gp-practice/january-2019)
