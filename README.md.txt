📚 What This Project Is
This project shows how to use Azure Databricks with Azure Data Lake Storage Gen2 (ADLS Gen2) to read different types of files, process and filter data using both Python and SQL, and save the results as a Delta table. It’s built to help you learn how to work with big data in the cloud using simple steps and clear examples.

📋 Steps I Followed In This Project
Set Up and Mount Storage:

Connected Databricks to my Azure Storage so it can read files directly.

Ran a command to see all the files in my storage.

Read Files into Spark DataFrames:

Loaded CSV, JSON, TSV, and TXT files using sample Python code.

Create Temp Views for SQL:

Made each DataFrame available as a SQL "table" (temp view) so I could use SQL queries.

Query and Transform Data:

Used SQL to filter, count, or group data (for example, finding all customers with an email address).

Create a Delta Table (Save Processed Data):

Saved filtered data as a Delta table, which is a special format for big data projects.

Check Results & Document:

Ran example SQL queries on the Delta table to show it works.

Took screenshots at each important step to show the process.

▶️ How To Run This Project
Open the notebook (Connect to ADLS Gen2.ipynb) in your Databricks workspace.

Go through each code cell, one at a time—they are in order.

Replace authentication codes (client ID, secret, etc.) with your own values (never share these online).

After running each cell, check the output and screenshots for what you should see.

📝 Requirements
Azure Databricks (Workspace and an active cluster)

Azure Data Lake Storage Gen2 (a storage account and a container with your files)

Service Principal with Client ID, Client Secret, and Tenant ID (for secure authentication)

Some sample data files (CSV, JSON, TSV, TXT) in your storage