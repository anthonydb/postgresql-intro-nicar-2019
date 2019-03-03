# PostgreSQL Hands-On · NICAR 2019 Newport Beach, Calif.

## Description
This session will introduce you to PostgreSQL, a free, open source relational database system similar to MySQL and Microsoft SQL Server. We’ll cover the PostgreSQL ecosystem, from the database itself to management tools such as pgAdmin and psql. We’ll also dig into some of PostgreSQL’s unique and super-handy features, including the PostGIS spatial database extension, full-text search, and statistical functions.

This repo includes data, sample queries, and a [PDF of slides](https://github.com/anthonydb/postgresql-intro-nicar-2019/blob/master/NICAR-2019-PostgreSQL.pdf). The material is drawn from the more advanced chapters of this author's book [Practical SQL](https://www.nostarch.com/practicalsql). You can find all the code examples and data for the book [here](https://github.com/anthonydb/practical-sql).

## Topics
* A few basic queries
* Creating a function
* Spatial queries with PostGIS
* Full-text search
* Statistical functions


## Setup
If you're trying this at home, here's how to get rolling (you will need to have PostgreSQL installed, along with the PostGIS extension).

* Download this repo to your computer.
* To create tables and load data, execute the queries in the file [pg_create_import.sql](https://github.com/anthonydb/postgresql-intro-nicar-2019/blob/master/pg_create_import.sql) using pgAdmin, the psql command-line tool, or another GUI. Note that you will need to load a Census shapefile using a command-line utility noted at the end of the file.
* You can then run the queries in [pg_demo_queries.sql](https://github.com/anthonydb/postgresql-intro-nicar-2019/blob/master/pg_demo_queries.sql)
