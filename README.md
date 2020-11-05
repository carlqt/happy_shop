# Happy Shop

# Features!
  - API Docs on /api-docs

# Dependency
Docker v2.5 and/or above

# Installation
Clone this repository

# How to run
## If you have `make`, here are the commands you can use
- `make start` - Starts the app and use the cached image
- `make build_and_start` - Rebuilds images and starts the app

## If not
use `docker-compose up`

# Migration
run `make migrate` to run the migration and db seeding

### Access
`localhost:3000` for your happy shop

### API Docs

The api docs is powered by Swagger-UI and can be accessed on `localhost:8000/api-docs`

