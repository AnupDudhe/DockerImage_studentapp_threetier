FROM mysql:latest

LABEL database="studentapp"

COPY student.sql /docker-entrypoint-initdb.d/

CMD /bin/bash
