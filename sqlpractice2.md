-- Import practice
-- General syntax
COPY table_name
FROM 'C:\YourDirectory\your_file.csv'
WITH (FORMAT CSV, HEADER);

	1. Import data from the csv
		>create table ifnotdef
		>make it avialable for postgres
		>import selected information
	2. Export Data
		>use queries to search what you are looking for, with delimitations.
		>copy info to our export files