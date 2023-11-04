# python-web-flask-mvc-dolt-simple

## Description
Creates a datatable of `dog` for a flask project.

If path is not found, will default to 404 error.

## Tech stack
- python
  - flask
  - sqlalchemy
- bootstrap
- jquery
- dataTable
- dolthub/dolt-sql-serverdb

## Docker stack
- python:latest
- dolthub/dolt-sql-serverdb:latest

## To run
`sudo ./install.sh -u`
- [web app](http://localhost)

## To stop (optional)
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
- https://stackabuse.com/using-sqlalchemy-with-flask-and-postgresql/
- https://stackoverflow.com/questions/27766794/switching-from-sqlite-to-dolt-with-flask-sqlalchemy
