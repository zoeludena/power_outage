# power_outage

### Dataset:
<a href = "https://www.sciencedirect.com/science/article/pii/S2352340918307182"> **Data Dictionary**</a>: Found under *Table 1. Variable descriptions*.

<a href = "https://engineering.purdue.edu/LASCI/research-data/outages:"> **Download Here**</a>


### Notes:

It would be preferable if these two columns were combined into one pd.Timestamp column. Combine 'OUTAGE.START.DATE' and 'OUTAGE.START.TIME' into a new pd.Timestamp column called 'OUTAGE.START'. Similarly, combine 'OUTAGE.RESTORATION.DATE' and 'OUTAGE.RESTORATION.TIME' into a new pd.Timestamp column called 'OUTAGE.RESTORATION'
