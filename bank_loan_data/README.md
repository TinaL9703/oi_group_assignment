# bank_loan_data
1. get_branch_data_dev.ipynb
	- code for getting the branch's locations and convert those location into longitude and latitude
	- output: branch_locations.csv
2. branch_locations.csv
	- contains the location, longitude and latitude for each branch(bank)
3. PSV_SUBURB_HOUSE_1stQrt_2022.xlsx
	- edited version of data from https://discover.data.vic.gov.au/dataset/victorian-property-sales-report-median-house-by-suburb# 
	- contains the median house price and the No. of sales for each suburb in Victoria
4. get_bank_and_loan_data.ipynb
	- code for generating the data loans and the bank capacity for each bank
	- inputs: branch_locations.csv, PSV_SUBURB_HOUSE_1stQrt_2022.xlsx
	- outputs: bank.csv, loan.csv
5. bank.csv
	- contains the location, longitude, latitude and capacity for each bank
	- 169 rows
6. loan.csv
	- contains the amount and type for each loan
	- 21096 rows