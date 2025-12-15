# Thesis
Code files used in graduation thesis
This repository provides supporting code for the MSc dissertation 
"Assessing accessibility equity of tram and public bus network in Greater Manchester".

Due to data licensing restrictions (OS Open Roads, OAC 2021, IMD 2019),
Raw spatial datasets are not included in this repository.
The analytical workflow and data processing steps are fully described
in the Technical Appendix submitted with the dissertation.

Repository contents:
- Gini & Moran.ipynb:
  Computes inequality (Gini coefficient) and spatial autocorrelation (Moran’s I)
  using the final integrated LSOA-level dataset described in Appendix A.

- Logist.ipynb:
  Performs regression analysis on accessibility and socioeconomic indicators.

These notebooks were executed on the final dataset
"GM_LSOA_FinalIntegratedDataset.csv", generated through the GIS and SDNA
workflow described in the Technical Appendix.

Note on dataset naming:
The final integrated dataset used for all statistical analyses is named
"ng_with_EXPzhong.csv" in this repository.

In the Technical Appendix submitted with the dissertation, this dataset is
referred to generically as "GM_LSOA_FinalIntegratedDataset.csv" to indicate
Its role is the final analysis-ready LSOA-level dataset.

These two names refer to the same dataset, and no differences exist in the data
content, variables, or records.

No analytical methods, data, or results were modified after the project
submission deadline (1 December 2025).
