Alaska Airlines BI Exercise

This repo contains SQL used to compute various KPIs for my presentation.   I'm using Duck DB to pull some summary metrics to be used in the presentation.     


How to run:
1. Install DuckDB
2. Save the Sample data as a csv file
3. Upload to Duck DB as a table called:  ca_candidate_project_data
4. Ensure column data types so that numerical values are stored as integer or double; month is stored as date.   I had to make sure the csv file saved numbers without commas.   I have stored off column data types in Describe_Output.csv
6. Run the SQL Files 
