# Exchange-Rate-Reporter

## Description: ##
Exchange-Rate-Reporter is a simple python based script to query Yahoo Finance or Heroku Exchange Rate Web App and return you the exchange rates for the currencies of your preference.

**exchange_rate_reporter.py** - This script is based on python 2 and query both yahoo finance and heroku exchange rate and print them respectively

**exchange_rate_reporter_cloudwatch.py** - This script is based on python3 and query yahoo finance and upload the results to AWS CloudWatch as a custom metric under name space ExchangeRate. The metric is uploaded to us-east-1 region.

##Usage##

    usage: exchange_rate_reporter.py [-h] [-f FROM] [-t TO] [--version]
    
    usage: exchange_rate_reporter_cloudwatch.py [-h] [-f FROM] [-t TO] [--version]

If -f and -t is not mentioned, then by default the script will report the conversion rate from EUR to INR.
