web: gunicorn --bind 0.0.0.0:8080 app:server --log-file=-
worker-default: celery -A tasks worker --loglevel=info
worker-beat: celery -A tasks beat --loglevel=info