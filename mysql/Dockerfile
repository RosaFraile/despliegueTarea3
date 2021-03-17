FROM mysql:5.7

RUN echo [mysqld] >> /etc/mysql/my.cnf
RUN echo "innodb_use_native_aio=0" >> /etc/mysql/my.cnf

ENV MYSQL_ROOT_PASSWORD root
ENV MYSQL_USER dwes
ENV MYSQL_PASSWORD dwes
ENV MYSQL_DATABASE dwes

EXPOSE 3306
