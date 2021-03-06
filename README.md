# Forum App in React & Redux + Django

```
Forum App, with a frontend built in React & Redux and a backend built in Django API.
```

## Live Demo

**This App uses a Heroku free plan, so I am afraid that it takes time to load the pages.**

Check out [FRONTEND LIVE DEMO](https://symantic-frontend.herokuapp.com/) here!!

Check out [API LIVE DEMO](https://forum-prod-api.herokuapp.com/) here!!
![image](https://user-images.githubusercontent.com/95646459/146615731-cbc97b72-96b7-451c-9f8a-a532a5862276.png)


#Backend 
![image](https://user-images.githubusercontent.com/95646459/146840250-c675df5f-4e0a-41d7-9a0a-7ee40cdc22e1.png)


## Tech used

```
* Frontend : React & Redux
* Backend : Django
```

## How to Install

1. Git Clone

```
git clone git@github.com:Tech-i-s/techis-wd-forum-django-react.git
```

2. Backend setting

```
cd backend
Python -m venv env
(For Mac) source env/bin/activate
(For Windows) env/Scripts\activate
pip install -r requirements.txt
python manage.py makemigrations
python manage.py migrate
python manage.py runserver
# Open http://127.0.0.1:8000/posts/

# To have dummy data for testing run:
python manage.py fixtures/dummy-data.json
```

3. Frontend setting

```
cd frontend
npm install
npm start
# Open http://127.0.0.1:3000/
```
