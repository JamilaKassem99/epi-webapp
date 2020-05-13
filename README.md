# epi-webapp
At this step the database is created and the webserver is in place with Django.
How to migrate:
1- Install Django https://docs.djangoproject.com/en/3.0/intro/tutorial01/
2- Unzip Copy/paste the file in the specified directory (ex: Home/mysite)
3- Migrate models. You can see the commands to do so in the toturial link: python manage.py migrate
4- Run: python manage.py runserver
5. Go to http://127.0.0.1:8000/admin/ to add to the database
6. Run: ./manage.py shell < create_areas.py to run the python code
