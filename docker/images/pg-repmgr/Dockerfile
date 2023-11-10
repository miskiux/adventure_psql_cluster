FROM pg-base

RUN apk update && apk add postgresql15 repmgr

COPY ./config/pg_hba.conf /etc/postgresql/pg_hba.conf
COPY ./config/postgresql.conf /etc/postgresql/postgresql.conf