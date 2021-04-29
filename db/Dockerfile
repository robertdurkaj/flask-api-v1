FROM postgres:13.2-alpine

COPY init_db.sql /docker-entrypoint-initdb.d/

ENV POSTGRES_DB=cars_api
ENV POSTGRES_USER=postgres
ENV POSTGRES_PASSWORD=postgres
