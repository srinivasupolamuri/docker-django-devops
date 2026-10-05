# Django Docker DevOps

A containerized Django web application created to understand and demonstrate
Docker and DevOps fundamentals using a real Django application.

## Project Overview

This project demonstrates how to:

- Build a Django web application
- Create a Docker image using a Dockerfile
- Run the Django application inside a Docker container
- Map container ports to the host machine
- Manage Docker images and containers
- Use `.dockerignore` and `.gitignore`
- Monitor application logs
- Execute commands inside a running container
- Start, stop and remove Docker containers
- Version-control the project using Git and GitHub

## Technology Stack

- Python
- Django
- Docker
- Git
- GitHub
- Linux / WSL2

## Project Structure

```text
django-docker-devops/
│
├── .dockerignore
├── .gitignore
├── Dockerfile
├── requirements.txt
├── README.md
│
└── devops/
    ├── manage.py
    ├── db.sqlite3
    ├── demo/
    │   ├── admin.py
    │   ├── apps.py
    │   ├── models.py
    │   ├── urls.py
    │   ├── views.py
    │   └── templates/
    │       └── demo_site.html
    │
    └── devops/
        ├── settings.py
        ├── urls.py
        ├── asgi.py
        └── wsgi.py
