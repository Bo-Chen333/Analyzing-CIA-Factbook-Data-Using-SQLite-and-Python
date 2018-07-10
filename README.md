# Analyzing-CIA-Factbook-Data-Using-SQLite-and-Python
=======================================================

Overview of the Data(Step 1)
-------------------------------------------------------
Import pandas and sqlite3.<br>
Connect to `factbook.db` and use `pandas.read_sql_query()` to return information on the tables in the database.<br>
Write and run another query that returns the first 5 rows of the `facts` table in the database.<br>

Summary Statistics(Step 2)
-------------------------------------------------------
Write a single query that returns the:
* minimum population
* maximum population
* minimum population growth
* maximum population growth

Exploring Outliers(Step 3)
-------------------------------------------------------
Write a query that returns the countrie(s) with a population of `0`.<br>
Write a query that returns the countrie(s) with a population of `7256490011`.<br>
In a markdown cell, type up your observations on these rows.<br>

Histograms(Step 4)
-------------------------------------------------------
Using just the non-outlier rows, generate a 2 by 2 grid of histograms for the following columns:
* `population`
* `population_growth`
* `birth_rate`
* `death_rate`
