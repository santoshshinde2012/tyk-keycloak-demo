## TYK Keycloak Demo

Demonstrates how to use Tyk Gateway to protect a Node JS API, denying access to it without an OIDC token from a Keycloak instance.
 
Please add the following lines to your `/etc/hosts`:

```
127.0.0.1       oidc
127.0.0.1       tyk
```

## Run 

`docker-compose up`
