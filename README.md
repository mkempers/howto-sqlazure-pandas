# How to read and write to an Azure SQL database from a Pandas dataframe
The code is very basic and self-explanatory. The main code can be found in *main.py*. Here is what is happening:
1. The following constants are set:
⋅⋅* Azure SQL database userid
⋅⋅* Azure SQL database password
⋅⋅* Azure SQL database server name (fully qualified)
⋅⋅* Azure SQL database name (if it does not exit, pandas will create it)
⋅⋅* Azure SQL database table name
⋅⋅* ODBC Driver, there are several guides out there on how to set this up on different OS's
... You should replace these with your own values
2. Building the right connectionstring for azure sql and the odbc driver 
3. Read dummy data from CSV into a dataframe
4. Create SQL Alchemy engine and write data to SQL
5. Read data from SQL back into a dataframe
