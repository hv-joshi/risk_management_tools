# risk_management_tools
Web Scraping and reading OORfiles

# Documentation:

## Prerequisites

1. Python 
2. Jupyter Notebook
3. Install The required Libraries:  
  
Run the Following in the Command Line 
``` 
pip install -r requirments.txt
```
(It is Recommended to create a virtual environment)
## Running The Tools:

### Web Scraping:

1. Download Web_Scraping.ipynb in a seperate directory
2. Run the file and enter the Date when prompted
3. It will create a directory with an excel Workbook named by the date
4. if the date selected isnt present in the database of CME it will return an error
5. If this happens just run the file again with a different date
6. All runs will create the Workbooks in the same directory

### Position Pivot Tables:

1. Download Positions.ipynb into a direcctory(the same would be used for DoD not finished yet(TDTC File stuff))
2. The directory should also have the OOR file for that day named specifically as today.csv
3. Run the entire File and enter input when prompted
4. It will create group files for the grouped units with the name given
5. It will contain an excel workbook with the different pivot tables
