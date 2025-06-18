FROM mysql:latest
ENV MYSQL_ROOT_PASSWORD=fernanda
ENV MYSQL_DATABASE=concesionario
ENV MYSQL_USER=fernanda
ENV MYSQL_PASSWORD=fernanda

COPY concesionario.sql /docker-entrypoint-initdb.d/
