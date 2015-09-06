# django-rest-boilerplate
A Django + REST API Boilerplate code with a custom user object

### Motivation
This is a boilerplate template for a Django REST framework which implements a custom AbstractBaseUser
with support for Django Admin and basic class based generic serializers and views for viewing the account object.

This is intended to be compatible with an AngularJS Boilerplate Code and Ionic Boilerplate Code Sample

### Setup
1. Create a virtual env
```$ virtualenv env```
2. Source and install the dependencies
```$ source env/bin/activate```
```$(env) pip install -r requirements.txt```
3. Sync the Database
```$(env) cd drb```
```$(env) python manage.py migrate```
4. Create a superuser object
```$(env) python manage.py createsuperuser```
5. Run the server
```$(env) python manage.py runserver```


### Endpoints
Currently there are two main endpoints
```/admin```
```/api/v1```
