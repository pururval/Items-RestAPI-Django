Django REST API
===============

## Usage

```python3 -m venv env
source env/bin/activate  
pip install django
pip install djangorestframework
```
```
python3 manage.py makemigrations        
python3 manage.py migrate               
```
```
python manage.py createsuperuser --username admin --email admin@example.com
```
```
python3 manage.py runserver
```
### Authentication
Login in the admin at
`http://localhost:8000/admin`


### Register an application

To obtain a valid access_token first, register an application, just point your browser at:

`http://localhost:8000/o/applications/`

More at [django-oauth-toolkit](https://github.com/jazzband/django-oauth-toolkit/blob/master/docs/rest-framework/getting_started.rst)

## Create items: POST endpoint
`http://localhost:8000/items/`
![Post: Create Items](/img/postcreate.png)


## List items: GET endpoint
`http://localhost:8000/items/list/`
![Get: List items](/img/getlist.png)

## Update items: GET/PUT/DELETE endpoint
`http://localhost:8000/items/1`

![Put/Delete: Update items](/img/putdelete.png)

