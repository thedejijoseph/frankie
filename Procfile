release: python manage.py migrate
release: python manage.py collectstatic --clear --no-input
web: gunicorn frankie.wsgi
