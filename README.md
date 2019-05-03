# ExtractUpdateVendor
This project is to:-
Log into Acme test site,navigate to display all Vendors and extract all vendors data in datatable
Transaction item is datarow, navigate to individuatl TaxId and fetch the individual vendor details
In process, check if the vendor details fetched in step 2 matches with that in step 1 i.e. in entire data table.
If matches then second check is to check if city is particular to value configured in the config file.
If both the check matches, update the results in results.csv file.
If first match failes, raise Business rule exception 1, value configured in config file
If second match fails, raise Buisness rule exception 2, value configured in config file.
