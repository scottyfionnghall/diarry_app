# Diary App

An RESTful API for a Diary web-site. This app is database powred by PostgreSQL. Implements an authorization by using OAuth Bearer Token in a form of JWT(JSON Web Token).

## Endpoints


```
POST /auth/register - an endpoint to register users
POST /auth/login - an endpoint to login with a credentials
POST /api/entry - a secure endpoint to post an entry to the app.
                  Requires a bearer token, wich is returnd upon using /auth/login.
GET /api/entry - a secure endpoint to get all users entires.
```