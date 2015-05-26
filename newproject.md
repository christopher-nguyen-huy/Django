# Setup a new project
## Create project
```
django-admin startproject mysite
```

## Database
Open file mysite/settings.py

**Available databases**:
- 'django.db.backends.sqlite3'
- 'django.db.backends.postgresql_psycopg2'
- 'django.db.backends.mysql'
- 'django.db.backends.oracle'

For sql server, use Pyodbc library
## Timezone
mysite/settings.py

Montreal is CA

## Launching server
In repository launch
```
python manage.py runserver [port number]
```
port number is 8000 by default
