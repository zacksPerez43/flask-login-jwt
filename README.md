# flask-login-jwt

Login que genera un token que es usada dentro del siguiente repositorio: 
[Link al repositorio](https://github.com/zacksPerez43/cancer_de_mama)

Conectada a una BD de supabase.

## API Reference

#### Get item

```http
  GET /login
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `username`      | `string` | **Required**.|
| `password`      | `string` | **Required**.|
