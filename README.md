# sec-public-company-bankruptcy-analysis
## Overview
This is an exploration of a dataset made available by the Securities and Exchange Commission of public companies filing for bankruptcy between the fiscal years 2009-2011. This project leans into using charts to demonstrate findings. Overall, the project finds a strong concentration and skew in bankruptcies. A small number of states dominate activity - namely Delaware is a leader in filing volume and New York accounts for the majority of total assets and liabilties. This lends credance that large outlier cases drive much of the overall scale while typical filings are relatively small.
Dataset source: https://catalog.data.gov/dataset/public-company-bankruptcy-cases-opened-and-monitored

## Filings per year (trend)
* 2009 has twice the filings than the 2 successive years
* 2010 and 2011 are nearly equal to one another
* Dataset contains bankruptcy filings across only 3 years. This limits the usability of the dataset for explaining or predicting yearly trends

<img width="752" height="452" alt="image" src="https://github.com/user-attachments/assets/3ad9be86-7ffb-4333-8151-d11e74fd81d7" />

## Filings by court/state (ranked)
- Total filings skews heavily towards a handful of states. Namely the top 5 states contain about 70% of all filings across the country
- There is a long tail
<img width="752" height="452" alt="image" src="https://github.com/user-attachments/assets/abff2774-b32b-428a-8104-e29be912889b" />

## Total assets, total liabilities by year and by state
- Top 5 states compose 98% of total assets AND 98% of total liabilities
- New York alone composes the majority of total assets and liabilities in bankruptcy filings. New York has about 80% of all assets and about 85% of all liabilities
- There is a long tail

<img width="752" height="452" alt="image" src="https://github.com/user-attachments/assets/2ea8341a-87f1-4ce0-a13c-d8fa3bea0c30" />

## Median/P90 assets/liabilities by year
- Median assets remained stable, rising slightly over time
- Median liabilities increased in 2010 but sharply declined the following year
* P90 Assets and liabilities dramatically decreased in 2010 and 2011
* When considering the trends in medians, this suggests 2009 had uniquely large filings but the typical filing was relatively unchanged
<img width="752" height="452" alt="image" src="https://github.com/user-attachments/assets/ba22d81d-425b-4d24-b623-c8984d57d666" />
<img width="752" height="452" alt="image" src="https://github.com/user-attachments/assets/b2061ab3-6d3c-4912-a73c-278d00d0bb1e" />
