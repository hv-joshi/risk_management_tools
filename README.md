# risk_management_tools
Web Scraping and reading OORfiles

# Documentation:

## Running The Tools:
### Prerequisites

1. Python 

2. Install The required Libraries:  
  
Run the Following in the Command Line 
``` 
pip install -r requirments.txt
```
(It is Recommended to create a virtual environment)

### Web Scraping:

1. Download Web_Scraping.ipynb in a seperate directory
2. Run the file and enter the Date when prompted
3. It will create a directory with an excel Workbook named by the date
4. if the date selected isnt present in the database of CME it will return an error
5. If this happens just run the file again with a different date
6. All runs will create the Workbooks in the same directory.
