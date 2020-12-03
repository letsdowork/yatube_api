# Yatube API
## Provides the service's API for publishing personal diaries.
___
The JWT token is used for authorization. You can get it by making a POST request with the "username" and "password" fields. When sending the request, pass the token to the header Authorization: Bearer &lt;token&gt;.

The project is based on the Django Framework. To run it on a local machine, use the command: python manage.py runserver.
Detailed API documentation is available at the local address 127.0.0.1/redoc.
