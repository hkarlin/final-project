This project analyzes 119,491 NYC Department of Buildings complaints filed in 2025, sourced from NYC Open Data via the Socrata API. The data was cleaned and enriched in Python using pandas, then queried in SQL using an in-memory SQLite database. Two sklearn models were built to predict resolution time and access denial outcomes, both of which performed near chance, suggesting the current dataset lacks the features needed for reliable forecasting.

Key findings: 
1) Illegal Conversion is the highest-volume and slowest-resolving complaint type (135.6 days average)
2) Queens has a 30.9% access denial rate and 71-day average resolution time that outpaces every other borough
3) Nearly 1 in 4 complaints citywide closes with no enforcement action taken.

A supplementary cross-reference with Census ACS income and poverty data found no meaningful correlation with enforcement speed, pointing instead to building type and complaint complexity as the primary drivers.

[DOB_Complaint_Analysis_2025.pdf](https://github.com/user-attachments/files/28236185/DOB_Complaint_Analysis_2025.pdf)
