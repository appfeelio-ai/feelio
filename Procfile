release: python manage.py migrate --no-input && python manage.py collectstatic --no-input && python manage.py loaddata resources/fixtures/helplines.json resources/fixtures/articles.json
web: gunicorn feelio.wsgi --log-file -
