app setup
# pip3 install virtualenv
# virtualenv env
# source env/bin/activate
# python3 app.py

access database
# python3
# from app import db
# db.create_all() // create database

deployment on heroku
# pip3 install gunicorn
# pip3 freeze > requirements.txt
# touch Procfile
# git push heroku master