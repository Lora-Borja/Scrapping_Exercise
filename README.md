# Scrapping_Exercise

Looking for dataset on IPOs to scrape for our final group project.

Scrapped IPOs 2020 data from: https://stockanalysis.com/ipos/2020-list/
I was able to scrape the data rows but not the column headers with it.
I was able to put the list into a DataFrame but since there are no column headers all of the data ended up in one column.
I tried to see if I can slice / group the rows by the 5 columns we need but unsuccessful - anyone have any idea?
I exported the DataFrame into a CSV (IPO2020_cleaned attached) and my ipynb file for the scrapping codes also attached.

As a manual workaround for now I sorted the IPO2020 data in excel and transposed the rows into the columns needed (see IPO2020_sorted).
