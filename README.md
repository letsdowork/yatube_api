# Yatube API
## Provides the service's API for publishing personal diaries.
The JWT token is used for authorization. You can get it by making a POST request with the "username" and "password" fields. When sending the request, pass the token to the authorization: Bearer <token> header.
The project is based on the Django Framework. to run it on a local machine, use the command: python manage.py runserver.
Detailed API documentation is available at the local address 127.0.0.1/redoc.
