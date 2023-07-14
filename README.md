## Install

`yarn`

## DB Setup

Copy .env.example to .env and set `DATABASE_URL` and `PORT`. Set PORT to 4000 to make sure that the Frontend application is compatible with the backend

Example for a local database: `DATABASE_URL=postgres://neill@localhost/pastebin`

You will need to create your own databases for this project locally.

Use SQL commands from create_tables.sql and insert_into_static_tables.sql to initiate the database with minimal data.

## Running locally

`yarn start:dev`

This will set the env var LOCAL to true, which will cause the db connection configuration to NOT use SSL (appropriate for your local db)
