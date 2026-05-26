FROM mysql:5.7.25
EXPOSE 3306
ENV MYSQL_ROOT_PASSWORD="devopspassword"
ENV MYSQL_DATABASE="accounts"
ADD db_backup.sql docker-entrypoint-initdb.d/db_backup.sql
