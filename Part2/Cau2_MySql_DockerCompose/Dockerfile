#tạo image từ mysql:8.0
FROM mysql:8.0

#set mật khẩu root, database, user, password
ENV MYSQL_ROOT_PASSWORD=rootpass
ENV MYSQL_DATABASE=dbDTL
ENV MYSQL_USER=userDTL
ENV MYSQL_PASSWORD=passDTL

#mở cổng 3306
EXPOSE 3306

#tạo volume cho dữ liệu mysql
VOLUME /var/lib/mysql

#chạy mysql server
CMD ["mysqld"] 