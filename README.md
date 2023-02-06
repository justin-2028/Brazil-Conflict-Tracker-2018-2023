# Brazil Conflict Tracker (2018-2023)

![](https://lh3.googleusercontent.com/WQLJZbrcPRbPpvcOxYxGm_NPkiuAtKnSiqQag83G9Lf-23MGYNZelcTvzCewYPuk3MjHsQuCArJYQAK3F63mMuXgh_32ZGyAjn6yKZ0fEDIdxfmDvE_YZ0vA2Yea82kXH1FZFxn2dg=w2400)

# DAY 1846 (January 1st, 2018 - January 20th, 2023)
This is a dataset that tracks **both non-violent and violent** conflicts in Brazil since 2018. **The January 8th invasion of Brazil's National Congress** by Jair Bolsonaro supporters served as inspiration for this dataset.

All data are official figures from the **Armed Conflict Location & Event Data Project (ACLED)** that have been compiled and structured by myself. The latest snapshot used from ACLED's *Latin America & the Caribbean* dataset was its January 20th, 2023 update and was last accessed on January 28th, 2023. From the regional dataset, conflict data from countries outside of Brazil were removed, along with ID-related variables provided by ACLED that offered minimal potential for statistical analysis.

# Data Sources
##### The primary data source used was the Armed Conflict Location & Event Data Project (ACLED), an organization that curates event data specifically designed for disaggregated conflict analysis and crisis mapping. ACLED has meticulously compiled conflict reports from the local, regional, national, and international level to ensure its quantity and quality.

1. [ACLED's Latin America & the Caribbean Regional Dataset](https://acleddata.com/curated-data-files/#regional) - Updated weekly, the regional dataset for Latin America & the Caribbean provided the conflict data for Brazil. The original dataset had to be cleaned thoroughly due to the vast number of ID-related variables and null values.
2. [ACLED's Codebook (January 2021)](https://acleddata.com/acleddatanew/wp-content/uploads/2021/11/ACLED_Codebook_v1_January-2021.pdf) - Cross-referencing with ACLED's Codebook clarified what events qualified as "conflicts" and the various functionalities that the data could provide.
3. [ACLED's Data Columns (April 2019)](https://acleddata.com/acleddatanew/wp-content/uploads/2021/11/ACLED_Data-Columns_v1_April-2019.pdf) - Unknown variable names from the ACLED's original Latin America & the Caribbean dataset were defined in this report.

# Statistics Being Tracked
- EVENT_DATE: The day, month and year on which a conflict event took place.
- EVENT_TYPE: The type of conflict.
- SUB_EVENT_TYPE: The type of sub-conflict. 
- ACTOR1: The named actor in the conflict.
- ACTOR2: The named actor associated with or identifying ACTOR 1.
- COUNTRY: The country in which the conflict took place (Brazil).
- LOCATION: The specific location in which the conflict took place.
- LATITUDE: The latitude of the location.
- LONGITUDE: The longitude of the location.
- SOURCE_SCALE: The scale (local, regional, national, international) of the source.
- NOTES: A short description of the conflict.
- FATALITIES: The number of reported fatalities that occurred during the conflict.

# Dataset History
2023-01-28 - Dataset is created (1854 days after temporal coverage start date).

[Kaggle Dataset](https://www.kaggle.com/datasets/justin2028/brazil-conflict-tracker-20182023) - The same data but on Kaggle.

# Code Starter
[Link to Notebook](https://www.kaggle.com/code/justin2028/conflicts-in-brazil-2018-2023-code-starter)

# Acknowledgements
Thank you once again to ACLED for enabling access keys to the necessary data!
Make sure to check out the Armed Conflict Location & Event Data Project (ACLED) at www.acleddata.com.
MLA Citation: “Curated Data For Latin America &amp; the Caribbean (20 January 2023).” ACLED, 10 Jan. 2023, https://acleddata.com/curated-data-files/#regional.
