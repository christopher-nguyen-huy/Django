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

## Create an app
```
python manage.py startapp someapp
```
- Fill out the `someapp/model.py`
- Activate the model in `mysite/settings.py`
```
INSTALLED_APPS = (
    'django.contrib.admin',
    'django.contrib.auth',
    'django.contrib.contenttypes',
    'django.contrib.sessions',
    'django.contrib.messages',
    'django.contrib.staticfiles',
    'someapp',
)
```
- Create the database schema from the model
```
python manage.py makemigrations someapp
```
- Execute the schema on the database
```
python manage.py migrate
```
