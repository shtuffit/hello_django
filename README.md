# hello_django

Basic template for running Django / Postgres with docker-compose

## Bring up the Django project in app/
1. `docker-compose up -d --build`
2. `docker-compose exec web python manage.py migrate --noinput`
3. `docker-compose exec web python manage.py createsuperuser`

## Bring things down
1. `docker-compose down`
