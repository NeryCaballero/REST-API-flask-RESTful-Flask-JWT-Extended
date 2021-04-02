# REST-API-flask-RESTful-Flask-JWT-Extended


jwt_ext is a totally diferent library than flask_jwt


1. install the library $ pip install flask-jwt-extended

2. from flask_jwt_extended import JWTManager

3. jwt = JWTManager(app)

> This does not creates the /auth endpoint, we have to create it ourselves.
> the file security with the functions authenticate and identity does not exixts anymore so
> we need to get rid of that import as well.

4. Create a user login Resource, which is going to do exactly what the authenticate function did before.
Is take in a username and password, and is going to make sure that they're correct.