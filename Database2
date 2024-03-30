LABEL database="studentapp"

ENV MYSQL_ROOT_PASSWORD=1234

# Copy initialization scripts (if any)
COPY student.sql /docker-entrypoint-initdb.d/


EXPOSE 3306

["mysqld"]

#CMD/bin/bash
#VOLUME /var/lib/mysql
