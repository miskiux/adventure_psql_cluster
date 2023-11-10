FROM postgres:15.1-alpine

COPY ./raw-data /raw-data
COPY ./dump.sql /docker-entrypoint-initdb.d/dump.sql

EXPOSE 5432/tcp