Explored a dataset of 3 million U.S. Amazon purchase records to build a multi-level sales and production dashboard in Power BI.

The raw data contained 1,800 distinct product categories. I reviewed each category and mapped it to one of 29 departments. That taxonomy was applied to the full dataset via a category-to-department join. These supporting data structures were then connected to the data model in Power BI.

The dashboard allows users to track revenue trends month-over-month, quarter-over-quarter, and same-period prior year — benchmarked against rolling historical averages which substitutes for budget targets — with breakdowns by geography, purchase behavior, and customer demographics.

Stack: Python [pandas, pandasql], Power BI, Excel
Data: The full dataset is not included due to size. It is available from:
Berke, A., Calacci, D., Mahari, R. et al. Open e-commerce 1.0, five years of crowdsourced U.S. Amazon purchase histories with user demographics. Sci Data 11, 491 (2024). https://doi.org/10.1038/s41597-024-03329-6
