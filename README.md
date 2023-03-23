# Crowdfunding_ETL
## Built an ETL pipeline using Python, Pandas, and Python dictionary methods to extract and transform the data. Next, created four CSV files and used the CSV file data to create an ERD and a table schema. The CSV file data was uploaded into a Postgres database from within Postgres, and then an additional alternate method of loading the tables was performed directly from the Jupyter notebook using SQLAlchemy.
### * Resources folder contains starting Excel files "crowdfunding.xlsx" and "contacts.xlsx".
### * Jupyter notebook file "ETL_Mini_Project_MLech.ipynb" used to extract, transform, and create new table data "campaign.csv", "contacts.csv", "category.csv", and "subcategory.csv".
### * An ERD of the four new tables "crowdfunding_db_schema.png" was created using QuickDBD, and the SQL file "crowdfunding_db_schema.sql" was used to create the tables in a new database "crowdfunding_db" in Postgres.
### * All four tables were imported in Postgres.
### * Additional alternate load was performed with SQLAlchemy, in which Python connected to the Postgres database, and the four tables were loaded directly from Jupyter notebook.