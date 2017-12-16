# 鲁道夫影视

鲁道夫影视社区是一个记录电影、分享电影、推荐电影的社区。


##  AngularJS + Flask

A template for building apps with an Angular frontend and a Flask / python backend.

### How to Get Started

1. install all the necessary packages
> pip install -r requirements.txt

2. run the app
> python runserver.py

3. create and seed the db (the server must still be running, so open a new terminal window first)
> python manage.py create_db && python manage.py seed_db --seedfile 'data/db_items.json'

4. check out your site
> http://localhost:5000
