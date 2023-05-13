# Django + Docker Cookiecutter
A little Cookiecutter to kickstart a simple Django project, inclusive of local development setup with Docker Compose.

# Local Development with Docker Compose

## Requirements
Ensure you have the following installed:
* [Docker](https://docs.docker.com/get-docker/)

Docker Compose should be included with current versions of Docker Desktop.

## Quickstart
```
$ docker compose up
```

## Running Commands
```
$ docker compose run --rm django python manage.py shell
$ docker compose run --rm django python manage.py createsuperuser
$ docker compose run --rm django python manage.py startapp example
```