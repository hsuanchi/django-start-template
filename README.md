# django-start-template

## Build Environment by Poetry
```
$ poetry init

$ poetry add django

$ poetry add --dev flake8 black

$ poetry export -f requirements.txt>requirements.txt
```

## Start Environment by venv
```
$ python3 -m venv venv

$ source venv/bin/activate

$ pip3 install -r requirements.txt
```

## Start Django Project
```
$ django-admin startproject app

$ python3 manage.py migrate

$ python3 manage.py createsuperuser

$ python3 manager.py runserver
```

## Set static


```
STATIC_ROOT = os.path.join(BASE_DIR, "static")
```

```
$ python manage.py collectstatic 
```
