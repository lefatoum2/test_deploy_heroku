release: python ./project_heroku/manage.py migrate
web: gunicorn project_heroku.wsgi --log-file=-