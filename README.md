# RPA Assessment – UiPath Project
# Instructions:
# Part 1 – Excel Data Cleansing & Manipulation:
	1.	Input file: Employees_Raw.xlsx
	2.	Workflow actions:
	  •	Remove duplicate rows
	  •	Standardize dates to YYYY-MM-DD
	  •	Format phone numbers to +20XXXXXXXXXX
	  •	Trim leading/trailing spaces in names and reduce multiple spaces to single
	3.	Output file: Employees_Cleaned.xlsx


 # Part 2 – Mails Consolidation:
	1.	Input file: Employees_Cleaned.xlsx
	2.	Workflow actions:
	  •	Split records by email domain: Internal → @corp.com and External → all others
	  •	Write results to a new Excel file: Sheet1 → Internal employees and Sheet2 → External clients
	3.	Output file: Employees_Splitted.xlsx


 # Part 3 – Web Automation:
	1.	Website: [Yahoo Finance – Most Active Stocks](https://finance.yahoo.com/markets/stocks/most-active/)
	2.	Workflow actions:
	  •	Kill Browser - Chrome
	  •	Extract data from the Most Active Stocks table (Symbol, Name, Price, Change, % Change, Volume)
	  •	Write results to Excel
	3.	Output file: MostActiveStocks.xlsx


