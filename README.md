# Adonis API application

This is the boilerplate for creating an API server in AdonisJs, it comes pre-configured with.

1. Bodyparser
2. Authentication
3. CORS
4. Lucid ORM
5. Migrations and seeds

## Setup

Use the adonis command to install the blueprint

```bash
adonis new yardstick --api-only
```

or manually clone the repo and then run `npm install`.


### Migrations

Run the following command to run startup migrations.

```js
adonis migration:run
```


Pronto!!!

Com esse token de autenticação que é gerado no login vamos conseguir validar nas requisições que precisam de autenticação, como um cadastro de simples, se o usuário é válido e está autenticado em nossa aplicação, primeiro projeto iniciando  quem quiser contribuir so da um fork no repositorio.
