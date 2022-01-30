# Pull official base image
FROM postgres:14-alpine

# Run create.sql on init
# Here, we extend the official Postgres image by //
# adding create.sql to the "docker-entrypoint-initdb.d" //
# directory in the container.
ADD create.sql /docker-entrypoint-initdb.d