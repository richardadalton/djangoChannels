# Django Channels Tutorial

Based on the following series.
https://channels.readthedocs.io/en/stable/tutorial/index.html

## Setup

### Install Requirements

$ pip install -r requirements.txt


### Run Redis

$ docker run -p 6379:6379 -d redis:5

##Running

* $ python manage.py runserver
* Open http://127.0.0.1:8000/chat/ in browser
* Enter a room name (e.g. lobby)
* Open the same room in another browner http://127.0.0.1:8000/chat/lobby
* Text entered in either browser will be displayed in both.