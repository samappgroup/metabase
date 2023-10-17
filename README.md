# Metabase Deployment files
A minimal buildpack replacement for our Heroku Metabase deployment.

## How To Deploy
1. Trigger a manual deploy of this branch in Heroku.
2. The latest version of Metabase gets deployed.

## Environment Variables
The container takes the following variables:

* `DATABASE_URL`: Automatically set by Heroku when attaching a Postgres instance. Contains a database URL
* `PORT`: Auto-set by Heroku. The HTTP port the container will listen on.
