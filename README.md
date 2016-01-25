# django-poll

Simple poll web-application.

#Prerequisites
- Docker installed
- Docker-compose installed

#Install
- Clone repository
- Run "docker-compose up -d" in project folder
- Migrate: "docker-compose run web python manage.py migrate"

Access at localhost:8000

To create superuser run "docker-compose run web python manage.py createsuperuser"
