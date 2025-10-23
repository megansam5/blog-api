## For creating a django project:

1. create virtual environment:

```
python -m venv .venv
```

2. Activate it

```
./.venv/Scripts/activate
```

3. Install django stuff

```
pip install django djangorestframework
```

4. Initialise django project

```
django-admin startproject <project_name>
```

5. Go into project

```
cd <project_name>
```

6. Create app/api

```
python manage.py startapp api
```

Then create models/views.

When ready to migrate to:

```
python manage.py makemigrations
python manage.py migrate
```

Then to run do:

```
python manage.py runserver
```
