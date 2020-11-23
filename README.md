# API-auth-JWT

###Metodos:

##POST:

``` 
http://localhost:8080/auth/criarUsuario
```

body em json:

{
  "nome": "Juan",
	"email": "a@a.com",
	"senha": "123"
}


##POST de login

``` 
http://localhost:8080/auth/login
```

body em json:

{
  "nome": "Juan",
	"email": "a@a.com",
	"senha": "123"
}

## GET

```
http://localhost:8080/auth/me/
```

body no header:

  Authorization  Gleidin_id {aqui o token que vai retornar}
