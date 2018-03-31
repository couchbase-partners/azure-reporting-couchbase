# azure-reporting
These are scripts to crunch Azure reports.  

## Usage
To run the usage script, you'll first need to download the Azure usage reports from [here](https://cloudpartner.azure.com/#insights/ordersandusage) as CSVs and put them in the usage directory.  After that you can run:

    python usage.py

## Revenue
To run the revenue script, download a CSV that starts in 10/1/14 and ends at the current date [here](https://cloudpartner.azure.com/#insights/payout), rename it to revenue.csv and put it in this directory.  After that you can run:

    python revenue.py
