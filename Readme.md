# EG Docker Frontend

Container for the frontend application of the Expungement Generator.


Basic usage of the frontend:

```
docker run natev/eg-docker-frontend -p 8080:80
```

You won't be able to accomplish much without a database, though, inluding logging in. So you'll need a database container running as well. natev/eg-docker-db provides a container with the right schema, and you cah check out compose files int this repository for examples of how to set up containers to run a full EG. 
