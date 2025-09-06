# RPA Assessment – PWC
# Instructions:
# Part 1 – Excel Data Cleansing & Manipulation (UiPath):
	1.	Input file: Employees_Raw.xlsx
	2.	Workflow actions:
	  •	Validate if the input file exists or no
   	  •	Remove duplicate rows
	  •	Standardize dates to YYYY-MM-DD
	  •	Format phone numbers to +20XXXXXXXXXX
	  •	Trim leading/trailing spaces in names and reduce multiple spaces to single
	3.	Output file: Employees_Cleaned.xlsx


 # Part 2 – Mails Consolidation (UiPath):
	1.	Input file: Employees_Cleaned.xlsx
	2.	Workflow actions:
 	  •	Validate if the input file exists or no
	  •	Split records by email domain: Internal → @corp.com and External → all others
	  •	Write results to a new Excel file: Sheet1 → Internal employees and Sheet2 → External clients
	3.	Output file: Employees_Splitted.xlsx


 # Part 3 – Web Automation (UiPath):
	1.	Website: [Yahoo Finance – Most Active Stocks](https://finance.yahoo.com/markets/stocks/most-active/)
	2.	Workflow actions:
	  •	Kill Browser - Chrome
	  •	Extract data from the Most Active Stocks table (Symbol, Name, Price, Change, % Change, Volume)
	  •	Write results to Excel
	3.	Output file: MostActiveStocks.xlsx


 # Part 4 – Python Coding Challenge:
	1.	Input file: Employees_Cleaned.xlsx
	2.	Script actions:
 	  •	Counts the number of unique companies
	  •	Finds the top 5 most common email domains
	  •	Counts the number of employees per company
	3.	Output file: Summary_Report.csv

# Requirements For Python Script:
 	1.	Python 3.10
	2.	Packages listed in requirements
	3.	Install dependencies:
 	  •	pip install -r requirements.txt
	4.	Use below code to run the script
 	  •	python Employees_Summary_Report_Method.py


 # assumptions:
 	1.	The input file structure is consistent with the one provided (Employees_Raw.xlsx), with the same column names
	2.	Date values may appear in multiple formats (e.g., dd-MMM-yy, yyyy-MM-dd, yyyy/MM/dd, dd/MM/yyyy) → workflow handles all
	3.	Phone numbers may be inconsistent (numeric, text, with dashes, spaces, or in scientific notation) → workflow normalizes them into +20XXXXXXXXXX.
 	4.	Employee names may contain multiple spaces → workflow trims and normalizes to single spaces


# Time Taken:
 	1.	Part 1 – Excel Data Cleansing: around 2 hours
	2.	Part 2 – Mails Consolidation: 30 minutes
	3.	Part 3 – Web Automation:  around 1.5 hours
 	4.	Documentation & Testing: 1 hour
  
 





