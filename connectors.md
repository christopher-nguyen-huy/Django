# MySql
## Mysqldb DEAD DO NOT USE
- *python 2*

```
pip install MySQL-python
```

## mysql-python USE THIS
- Requires:
	- Python and MySQL development headers and libraries
- *python 2 & 3*
- ENGINE: django.db.backends.mysql

```
pip install mysqlclient
```

## oracle-mysql
- *python 2 & 3*
- Does not require mysql, only python
- ENGINE: mysql.connector.django
- django 1.7
	- https://dev.mysql.com/doc/connector-python/en/connector-python-django-backend.html
	- `pip install mysql-connector-python`
- django 1.8
	- `pip install git+https://github.com/multiplay/mysql-connector-python`

#SQL Server
## django-pyodbc USE THIS
- *python 2*
- django 1.7
- SQL Server 2000, 2005, 2008, and 2012
- ENGINE: django_pyodbc

```
pip install django-pyodbc
```

## django-mssql
- *python 2 & 3*
- django 1.6 & 1.7
- SQL Server 2008/2008r2
- ENGINE: sqlserver_ado

```
pip install django-mssql
```
