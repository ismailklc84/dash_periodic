web: gunicorn app:server --bind=0.0.0.0:8000 --log-file=-
worker-default: celery -A tasks worker --loglevel=info
worker-beat: celery -A tasks beat --loglevel=info
