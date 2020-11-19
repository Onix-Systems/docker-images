FROM postgres:11

RUN apt-get update && \
    apt-get install -y \
        postgresql-11-postgis-3 && \
    apt-get clean
    
COPY docker-entrypoint-initdb.d/* /docker-entrypoint-initdb.d/
