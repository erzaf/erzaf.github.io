# GET
Get list of Users

> GET Endpoint : /users

Example success response:
```json
[
    {
        "email": "broto@email.com",
        "name": "broto"
    },
    {
        "email": "sudarmadji@email.com",
        "name": "darmadji"
    },
    {
        "email": "tuan_sugeng@email.com",
        "name": "Sugeng"
    },
    {
        "email": "namaku_hampir_jorok@email.com",
        "name": "Sentot"
    }
]
```
# GET {id}
Get data from a single Users

> GET Endpoint : /users/{id}

Example success response:
```json
{
    "email": "sudarmadji@email.com",
    "name": "darmadji"
}
```
# POST
Create a new User

> POST Endpoint : /users

Example request payload:
```json	
{
"email": "account@zz.com",
 "name": "input_username"
}
```
# PUT
Update/edit User

> PUT Endpoint : /users/{id}

Example request payload:
```json
{
"email": "account@zz.com",
 "name": "input_username"
}
```
# DELETE
Delete User

> DELETE Endpoint : /users/{id}