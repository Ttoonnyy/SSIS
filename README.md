# SSIS
Microsoft SQL Server Integration Services project with packages for: 
Inserting data to table from flat file (input_data). 
Extracting data from table to flat file (extract_data). 
Copying table data to "database warehouse"-type table with auditing columns for created and modified time and user.

Each package has data flow tasks within one control flow task only.
One package = one purpose

"load_transaction_source" solution item for reference. Includes stored procedures that won't be accessible.

Development:
Clean up the project a bit.
Add second database source to compare, sync, and publish to database warehouse with auditing fields.
Implement some kind of autonomy.

Note:
Package includes some redundant data flows. Will clean up ventually.
