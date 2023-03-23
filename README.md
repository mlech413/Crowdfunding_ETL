# Crowdfunding_ETL
## Built an ETL pipeline using Python, Pandas, and Python dictionary methods to extract and transform the data. Next, created four CSV files and used the CSV file data to create an ERD and a table schema. Finally, uploaded the CSV file data into a Postgres database.
### * Resources folder contains starting Excel files "crowdfunding.xlsx" and "contacts.xlsx".
### * Jupyter notebook file "ETL_Mini_Project_MLech.ipynb" used to extract, transform, and create new data "campaign.csv", "contacts.csv", "category.csv", and "subcategory.csv".
### * An ERD of the four new tables "crowdfunding_db_schema.png" was created using QuickDBD, and the SQL file "crowdfunding_db_schema.sql" was used to create the tables in a new database "crowdfunding_db" in PostgreSQL.
### * All four tables were imported in PostgreSQL.
### * Additional alternate load was performed with SQLAlchemy, in which Python connected to the PostgreSQL database, and the four tables were loaded directly from Jupyter notebook.