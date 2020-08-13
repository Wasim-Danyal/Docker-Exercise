# Derived from official mysql image (our base image)
FROM mysql:latest
# Add a database
ADD /trio-task/db/Createtable.sql
# Add the content of the .sql file to your image
# All scripts in docker-entrypoint-initdb.d/ are automatically
# executed during container startup
