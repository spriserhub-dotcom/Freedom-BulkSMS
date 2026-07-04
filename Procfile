web: gunicorn bulksms.wsgi:application
worker: celery -A bulksms worker -B --loglevel=info
