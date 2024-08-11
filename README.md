# AUTOMATION OF KPIS
<br>

## Compare Daily and Cumulative Annual Indicators

##### Description

This project focuses on automating the daily sales report delivery. It also includes calculating key performance indicators (KPIs) and sending them to managers and directors via email. The goal is to send a single page with the summarized information.

1. **Data** - 3 spreadsheets: Emails, Stores, Sales.
2. **Daily Task** - Send KPIs to managers and directors via email.
3. **Backup** - Save backups of the files.

### TEMPLATE OF ONE-PAGE SUMMARY TO BE SENT WITH KPI OVERVIEW

- **Daily Indicators**
- **Cumulative Annual Indicators**

<br>

  :DAY:                  | :Daily Value: | :Daily Target: | :Daily Status:
------------------------ | ------------- | -------------- | --------------
REVENUE                  | :8:           | :10:           |    []
PRODUCT DIVERSITY        | :7:           | :7:            |    []
AVERAGE TICKET PER SALE  | :9:           | :5:            |    []

  :YEAR:                 | :Annual Value: | :Annual Target: | :Annual Status:
------------------------ | ---------------| --------------- | ---------------
REVENUE                  | :8:            | :10:            |    []
PRODUCT DIVERSITY        | :7:            | :7:             |    []
AVERAGE TICKET PER SALE  | :9:            | :5:             |    []

<br>

## LIBRARIES USED

- pandas as pd
- pathlib
- yagmail

