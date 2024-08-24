# ToDo list web app

- [Backend](https://github.com/IldarGaleev/todo-backend-service)
- [REST API Gateway](https://github.com/IldarGaleev/todo-rest-gateway-service)

## Environment variable

| Name                      | Description                                                                                        |
|---------------------------|----------------------------------------------------------------------------------------------------|
| `BACKEND_SECRET_KEY`      | value for  backend `SECRET_KEY` env var                                                            |
| `BACKEND_SECRETS_MAX_AGE` | value for backend `SECRETS_MAX_AGE` env var                                                        |
| `ENV_MODE`                | value for backend and gateway `ENV_MODE` env var                                                   |
| `GIN_MODE`                | [Gin modes](https://pkg.go.dev/github.com/gin-gonic/gin#pkg-constants): `test`, `debug`, `release` |


## Utils

### Create new user

```bash
docker exec -it <backend-container-name> /app/createuser
```

