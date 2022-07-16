# MAC
#FROM arm64v8/mysql:latest

# Ubuntu
FROM mysql:latest
EXPOSE 3306 
COPY ./testdump.sql /docker-entrypoint-initdb.d/
