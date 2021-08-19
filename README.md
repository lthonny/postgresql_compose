# Postgresql & PgAdmin powered by compose

### Quick Start
- Clone or download this repository
- Go inside of directory, cd compose-postgres
- Run this command docker-compose up -d

### Environments
This Compose file contains the following environment variables:
- POSTGRES_USER the default value is admin
- POSTGRES_PASSWORD the default value is admin1234
- PGADMIN_DEFAULT_EMAIL the default value is pgadmin4@pgmail.org
- PGADMIN_DEFAULT_PASSWORD the default value is admin1234

### Access to postgres:
- localhost:5431
- Username: admin (as a default)
- Password: admin1234 (as a default)

### Access to PgAdmin:
- URL: http://localhost:5050
- Username: pgadmin4@pgadmin.org (as a default)
- Password: admin1234 (as a default)


### To Up the container
```
docker-compose --env-file ./.env up -d
```

#