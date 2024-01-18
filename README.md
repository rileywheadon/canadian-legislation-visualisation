# Havoc on the Hill
### A Visualisation of Canadian Legislation from 1994 - 2022
By Riley Wheadon


## Project Overview

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

## Findings

Between 2007 and 2010, Stephen Harper's minority conservative government had the most efficient parliament, as measured by the number of bills read. Justin Trudeau's government has had the lowest readings per day.

<img title="" alt="" src="/charts/images/fig-1-1.png">

On average, the frequency of bills passed by successives governments has decreased.

<img title="" alt="" src="/charts/images/fig-1-2.png">

The vast majority of bills in the Canadian parliament originate as private member's bills.

<img title="" alt="" src="/charts/images/fig-2.png">

If a bill makes it passed the first reading, it is very likely to receive Royal Assent. Additionally, the governor general has not rejected a bill passed by the government since 1994.

<img title="" alt="" src="/charts/images/fig-3.png">

Most bills are passed within 150 days of the first reading, but a few have been deliberated for over 1200 days.

<img title="" alt="" src="/charts/images/fig-4-1.png">

On average, the past four governments have spent the same amount of time deliberating each bill. 

<img title="" alt="" src="/charts/images/fig-4-2.png">

Surprisingly, the NDP have proposed the most bills to parliament, despite not forming government since 1994.

<img title="" alt="" src="/charts/images/fig-5-1.png">

Unsurprisingly, the government tends to propose more bills than the official opposition.

<img title="" alt="" src="/charts/images/fig-5-2.png">
