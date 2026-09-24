web: cd src && python manage.py migrate --noinput && python manage.py collectstatic --noinput && gunicorn lodestar.wsgi --bind 0.0.0.0:${PORT:-8000}
