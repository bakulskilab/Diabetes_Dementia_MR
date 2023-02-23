# Type 2 diabetes and dementia in the Health and Retirement Study: A Mendelian randomization approach

## Citation Information
Ware EB, Bustamante ACM, Fu M, Bakulski KM. Type 2 diabetes and dementia in the Health and Retirement Study: A Mendelian randomization approach. Alzheimer’s & Dementia. 2020;16(S10):e041220. doi:https://doi.org/10.1002/alz.041220

This Github repository contains the data management and analytic scripts to produce the following manuscript:[Type 2 diabetes and dementia in the Health and Retirement Study: A Mendelian randomization approach. Alzheimer’s & Dementia](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8044888/)

## Abstract
**Background**
Type 2 diabetes mellitus (T2DM) and dementia are leading causes of mortality and disability in the US. T2DM has been associated with dementia; however, causality has not been clearly established. This study tested inferred causality between T2DM and dementia status using a Mendelian randomization approach.
**Methods**
Participants (50+ years) from the 2010 wave of the Health and Retirement Study of European or African genetic ancestry were included (n = 10,322). History of T2DM was self-reported. Cognitive status (dementia, cognitive impairment non-dementia, or normal cognition) was defined from clinically validated cognitive assessments. Cumulative genetic risk for T2DM was determined using a polygenic score calculated from a European ancestry T2DM genome-wide association study by Xue et al. (2018). All models were adjusted for age, sex, education, APOE-ε4 carrier status, and genetic principal components. Multivariable logistic regression was used to test the association between cumulative genetic risk for T2DM and cognitive status. To test inferred causality using Mendelian randomization, we used the inverse variance method.
**Results**
Among included participants, 20.9% had T2DM and 20.7% had dementia or cognitive impairment. Among European ancestry participants, T2DM was associated with 1.66 times odds of cognitive impairment non-dementia (95% confidence interval: 1.55–1.77) relative to normal cognition. A one standard deviation increase in cumulative genetic risk for T2DM was associated with 1.30 times higher odds of T2DM (95% confidence interval: 1.10–1.52). Cumulative genetic risk for T2DM was not associated with dementia status or cognitive-impaired non-dementia in either ancestry (P > 0.05); lack of association here is an important assumption of Mendelian randomization. Using Mendelian randomization, we did not observe evidence for an inferred causal association between T2DM and cognitive impairment (odds ratio: 1.04; 95% confidence interval: 0.90–1.21).
**Discussion**
Consistent with prior research, T2DM was associated with cognitive status. Prevention of T2DM and cognitive decline are both critical for public health, however, this study does not provide evidence that T2DM is causally related to impaired cognition. Additional studies in other ancestries, larger sample sizes, and longitudinal studies are needed to confirm these results.

## Funding
Funding. This work was supported by the National Institutes of Health (grant nos. R01 AG055406, R01 AG055654, R25 AG053227, and P30 AG053760).

## Data availability
Publicly available datasets were analyzed in this study. This data can be found here: Health and Retirement Study health and covariate data are available here: https://hrs.isr.umich.edu/data-products. Health and Retirement Study genetic data are available here: dbGaP Study Accession: phs000428.v2.p2 (https://www.ncbi.nlm.nih.gov/projects/gap/cgi-bin/study.cgi?study_id=phs000428.v2.p2).

## Script Files
TwoSampleMR.Rmd: preparing for and conducting wo sample Mendelian randomization 

data_cleaning.Rmd: code for data cleaning

data_cleaning_newT2DPGS.Rmd: updated code for data cleaning with T2D PGS

main_analysis.Rmd: code for main analysis

sensitivity_analysis.Rmd: code for sensitivity analysis


