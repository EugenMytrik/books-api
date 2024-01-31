## 1. Install dependencies
```
pip install -r requirements.txt
```

## 2. Models migrate
```
py manage.py migrate
or
python manage.py migrate
```


## 3. Run command with demo data
```
py manage.py generate_authors
or
python manage.py generate_authors
```

## 4. Run Django web server
```
py manage.py runserver
or
python manage.py runserver
```

## Alternative version with Docker
## 1. Create password.txt file in db folder
## 2. Run docker-compose
```
docker-compose up --build
```