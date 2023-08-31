# FIFA21-Python
This projects is about data **cleaning** and **visualization** in **Python** on the FIFA 21 players data.

The dataset that is analyzed is on https://www.kaggle.com/datasets/yagunnersya/fifa-21-messy-raw-dataset-for-cleaning-exploring?select=fifa21_raw_data.csv

For this analysis the CSV file named "fifa21_raw_data.csv" was used.

## Deliverables

This project will clean data and provide visualizations on FIFA 21 player data in Python. Some of the cleaning that will be done in this project:

- Cleaning unnecessary "\n" from columns, i.e. from "Team & Contract"
- Splitting column data
- Appending the new data
- Separating MM/DD/YY (date) into Year, Month, Day columns
- Transforming data types, from strings to integers, i.e. €67.5M into numeric value
- Converting Height & Weight from inches and pounds to centimeters and kilograms

Some of the insights and visualisations done in this project:
- Which players are highly valuable but still underpaid? (Scatter plot)
- Top 10 clubs per average wage (Bar chart)
- Is there any correlation between the age of players and their market value? (Scatter plot)
- How is the age distribution of soccer players in the dataset? (Histogram & Kernel density plot)
- Top 10 clubs based on release clauses? (Violin plot)
