# A year of recovery from my Lisfranc fracture using data viz and moving average 

# Project description

Inception: You can find a more complete story of my left foot odessey on the [Medium post](https://medium.com/@isabelle.vea/looking-at-recovery-from-my-lisfranc-foot-fracture-using-data-viz-and-moving-averages-37a71a192bd1)


Data type: time series

Methods: moving average, data viz

Tools: Python (pandas, datatime, matplotlib, seaborn)


## Files included
- /data folder to put in the dataset
- StepAnalysis.ipynb : script where I visualize my step data
- apple-health-data-parser.py : this script is from [Markwk/qs_ledger repo](https://github.com/markwk/qs_ledger) and unmodified.


## Issues encountered (Feb 21 2023)
First time I exported my data from Health, there was an error with the two parsers I used, it turned out it was an issue from the app export. I just updated my iOS to version 16.3.1 and reexported the data from the app and the parser worked.

## Python packages needed
pandas, seaborn, datetime



# Credits
To parse and perform data prep and plotting moving averages, I used and was inspired by [Markwk/qs_ledger repo](https://github.com/markwk/qs_ledger)
