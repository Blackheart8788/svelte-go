### Handling SQL Migrations

for the Postgresql migrations in this project we are using the [migrate](https://github.com/golang-migrate/migrate/blob/master/database/postgres/TUTORIAL.md) package

#### Steps to run the current migrations on a local database

1. Install Postgresql on your machine: https://www.timescale.com/blog/how-to-install-psql-on-mac-ubuntu-debian-windows
2. Connect to your local database: "psql postgres"
3. Create a database: "CREATE DATABASE <database_name>;"
4. Run the migrations: ```task migrateUp```