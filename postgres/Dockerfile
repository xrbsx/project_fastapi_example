FROM postgres:alpine3.18

COPY init /docker-entrypoint-initdb.d/
RUN chown -R postgres:postgres /docker-entrypoint-initdb.d/
RUN chmod -R a+x /docker-entrypoint-initdb.d/