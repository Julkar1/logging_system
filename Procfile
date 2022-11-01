release: python manage.py migrate
web: gunicorn Logingend.wsgi
heroku ps:scale web=1