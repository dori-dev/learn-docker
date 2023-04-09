docker-compose up --build
docker-compose down
docker-compose up -d

export DJANGO_SUPERUSER_PASSWORD=admin
python manage.py createsuperuser --noinput --user admin --email admin@site.com