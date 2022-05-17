# _React + Django Rest Framework(API)_

## Run backend(Djanog)

### Now install Pipenv using pip:

```sh
pip install pipenv
```

### activate a new virtual environment:

```sh
pipenv shell
```

### Install

```sh
pipenv install django
pipenv install djangorestframework django-cors-headers
```

### Run migrations:

```sh
cd backend
python manage.py migrate
```

### Run

```sh
python manage.py runserver
```

## Run frontend(React)

### Install packages

```sh
npm install
```

### Run

```sh
npm start
```

### Code format using prettier

```sh
npx prettier --write .
```
