
[PostrgreSQL](https://www.postgresql.org/)

- object relational db
- case sensitive
- supports Python & JS

to initiate sql file in git terminal: `wget htps://file_name.sql`
to lounch: `psql` (if error connectin to server - `set_pg`)
to view / list db in PostgreSQL invironment: `postgres=# \l`
to create db: `CREATE DATABESA name`
to switch between db: `\c name`
to install db from file `\i name`
to connect to db and start server: `psql -d name`
to view tables from db: `\dt`

sample SQL query: `SELECT * FROM "Artists" WHERE "ArtistID" = 52 / 'Queen'`

[psycopg2](https://pypi.org/project/psycopg2/) is the most popular PostgreSQL database adpter for the Python programming language.

`pip3 install psycopg2`
to create .py file: `touch sql-psycopg2.py`


__Introducing an ORM__ - Object-Relational-Mapping (django, SQLAlchemy)

[SQLAlchemy](https://www.sqlalchemy.org/) (Expression language)

`pip3 install SQLAlchemy`
`touch sql-expression.py`

[SQLAlchemy](https://www.sqlalchemy.org/) (ORM - Class-based Models)

`touch sql-orm.py`


`touch sql-crud.py`



