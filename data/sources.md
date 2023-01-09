## Data Sources

### Raw

- bills.json - From https://www.parl.ca/legisinfo/en/bills?parlsession=all 
- mp.csv - From https://www.ourcommons.ca/members/en/search?parliament=all&caucusId=all&province=all&gender=all
- parliaments.csv - From  https://en.wikipedia.org/wiki/List_of_Canadian_federal_parliaments
- sessions.csv - From https://lop.parl.ca/sites/ParlInfo/default/en_CA/Parliament/parliamentsSessions
- sponsors.csv - Scraped from https://www.parl.ca/legisinfo/ in 02-scraper.ipynb

### Processed and Cleaned

- processed/bills_processed.csv - Processed data from bills.json - Preprocessing contained in 01-preprocessing.ipynb
- cleaned/bill_data.csv - Aggregation of data from bills.json, sponsors.csv, and mp.csv - See 03-cleaning.ipynb
- cleaned/parliament_data.csv - Aggregation of data from parliaments.csv and sessions.csv - See 03-cleaning.ipynb
