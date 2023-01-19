# Havoc on the Hill
### A Visualisation of Canadian Legislation from 1994 - 2022
### By Riley Wheadon

--- 

This project aims to identify trends in parliamentary bill data from 1994 to 2022 using the following Python libraries:
- Pandas
- Numpy
- Beautifulsoup4
- Plotly

The 'notebooks/' folder contains four .ipynb files which contain various stages of analysis:
1. preprocessing.ipynb - Preprocesses bill data by removing and aggregating columns
2. scraper.ipynb - A small web scraper built with Beautifulsoup4 to get data about the name, constituency, and role of bill sponsors.
3. cleaning.ipynb - Aggregates a number of raw data frames together to produce bills.csv and parliaments.csv, which will be used to generate visualisations.
4. visualisation.ipynb - Generates 8 charts describing the data in bills.csv and parliaments.csv

---
