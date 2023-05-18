# ETL-CSV-to-Excel
```Python 
import pandas as pd

csv_data=pd.read_csv('marketing_campaign.csv')

csv_data.to_excel('marketing_campaign.xlsx',index=False)

pip install openpyxl

csv_data.to_excel('marketing_campaign.xlsx',index=False)
```
