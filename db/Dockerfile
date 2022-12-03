FROM mysql:latest

ENV MYSQL_ROOT_PASSWORD=test
ENV MYSQL_DATABASE=reticula

COPY ./db/ /docker-entrypoint-initdb.d

