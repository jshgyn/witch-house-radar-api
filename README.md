# Radar API

Rails API for Radar Mobile App


## Example requests

#### Add User

 ```curl -d 'name=josh&email=josh@example.com&location=london&description=i love games' http://localhost:3000/users```

#### Modify User

```curl -d 'name=steve' -X PATCH http://localhost:3000/users/0```

#### Delete User

```curl -X DELETE http://localhost:3000/users/0```
