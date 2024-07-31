# Strapi CMS - Postgres and Docker

## Prerequisites

- Node.js 18
- Npm / yarn

### Development

Create _.env_ file with `NODE_ENV=development`

```
docker-compose up --watch
```

### Production

Create _.env_ file with `NODE_ENV=production`

```
docker-compose up --watch

```

### Envs

```
HOST=0.0.0.0
PORT=1337
APP_KEYS=
API_TOKEN_SALT=
ADMIN_JWT_SECRET=
TRANSFER_TOKEN_SALT=

# Database Local
DATABASE_CLIENT=postgres
DATABASE_HOST=
DATABASE_PORT=5432
DATABASE_NAME=
DATABASE_USERNAME=
DATABASE_PASSWORD=
DATABASE_SSL=false
JWT_SECRET=
NODE_ENV=

```
