web: gunicorn bluebee-dev.wsgi --log-file -
config:set DISABLE_COLLECTSTATIC=1
web: python manage.py collectstatic --noinput
web: python manage.py runserver "0.0.0.0:$PORT"
