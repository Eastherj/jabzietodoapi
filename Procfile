web: gunicorn todolistapi.wsgi
release: manage.py makemigrations --noinput
release: manage.py collectstatic --noinput
release: manage.py migrate --noinput
