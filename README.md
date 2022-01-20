# auth-api

Auth server with Role Based Access Control(RBAC) using a Access Control List(ACL).

**Specifications:**

- Regular users can READ
- Writers can READ and CREATE
- Editors can READ, CREATE, and UPDATE
- Administrators can READ, CREATE, UPDATE, and DELETE

Routes performing those actions will be protected by both a valid user and that user's permissions.

## Update log

v1.0.0

### Dependencies

TBD

### Routes

- POST /signup to create a user
- POST /signin to login a user and receive a token
- GET /secret should require a valid bearer token
- GET /users should require a valid token and "delete" permissions

#### UML

[Whiteboard](./assets/Auth-api.png)

#### Deployed link

Heroku

###### Auhtor: Scott Lease

