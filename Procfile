release: python manage.py makemigrations
release: python manage.py migrate --no-input
release: python manage.py runserver
web: gunicorn admin.wsgi
