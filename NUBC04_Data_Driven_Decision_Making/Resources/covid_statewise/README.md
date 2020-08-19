# Covid-19 Statewise Data, India
Data Source: https://www.mygov.in/corona-data/covid19-statewise-status/

## How to access data
For quick access, downlaod the .csv file and open it with Excel/Google Sheets etc, or open the .csv file right here and copy into excel. The data is as of Aug 18, 2020.

If you are using R, Rdata is for you and you probably know what to do with it.

Download xlsx only if for some reason the csv is not working for you. I do not recommend this because I might have used a depricated function for conversion of Rdata to xlsx.

## How to update data
If you want Aug 19 or the latest data for any day in the future, run the jupyter notebook top to bottom. The jupyter notebook uses an R kernet NOT a python kernel. WARNING: You have to manually enter in the data for the first row in the table from the data source, which if remains alphabetically sorted, is Andaman and Nicobar, in the R script. The code is commented to find out the exact place.