Sample for django rest application
====================================

It's a template for application based by django-rest-framework, postgreSQL and jwt-auth. It include docker-compose configuration file with db and app. Gunicorn is used as web server.

QUICK START
-----------
1. Install docker
2. Install docker-compose
3. Clone current repository
4. Run command in a path of location docker-compose.yml:

        docker-compose up --build api
        
    or

        sudo docker-compose up --build api

CHECK
-----------
If all is fine GET request to http://localhost:8880/health must be return 200_OK status code.