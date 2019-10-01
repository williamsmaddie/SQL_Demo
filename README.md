Call the cleanScript macro in the command line to execute.
NOTE: need to set pwd to SQL_Demo. This may require editing the first line of cleanScript.

cleanScript does the following:
- reads in cityName and cityPop from Excel-readable format (csv)
- eliminates duplicates in each file (IDs should be unique)
- joins data by ID
- exports cleaned data back to Excel-readable format
