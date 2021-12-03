# Derived from official mysql image (our base image)
FROM mysql
# Add a database
ENV MYSQL_ROOT_PASSWORD=root
ENV MYSQL_USER=paco
ENV MYSQL_PASSWORD=paco123
ENV MYSQL_DATABASE=escuela
# Add the content of the sql-scripts/ directory to your image
# All scripts in docker-entrypoint-initdb.d/ are automatically
# executed during container startup
COPY ./db-dump/ /docker-entrypoint-initdb.d/