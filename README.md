# Templates for django createproject and startapp

Each template will generate a custom structure for your django project or new app

### Project template structure (django_project.zip)
```
| apps ~> Directory to add your apps
  | __init__.py
| conf ~> Settings & config directory
  | __init__.py
  | asgi.py
  | wsgi.py
  | urls.py
  | settings
    | __init__.py
    | base.py ~> Main settings file
| manage.py
| readme.md
| .gitignore
| requirements ~> Directory to add requirements files
```


### New app template structure - THIS TEMPLATE WILL GENERATE AN API APP FOR DJANGO REST - (django_rest_app.zip)
```
| __init__.py
| api ~> Apiviews, serializers and urls
  | __init__.py
  | serializers
    | __init__.py
    | serializer.py
  | views
    | __init__py
    | view.py
  | urls.py
| apps.py
| mirations
  | __init__.py
| models -> Model's directory
  | __init__.py
  | model.py
| tests.py
```

#### How to use templates
- django-admin startproject --template=https://github.com/LeSZ0/django-templates/raw/main/django_project.zip
- python manage.py startapp --template=https://github.com/LeSZ0/django-templates/raw/main/django_rest_app.zip
