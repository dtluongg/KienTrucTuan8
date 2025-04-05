#tạo image từ nginx:alpine
FROM nginx:alpine


#copy file index.html vào thư mục /usr/share/nginx/html/
COPY index.html /usr/share/nginx/html/ 
#địa chỉ mặc định mà nginx sẽ tìm kiếm file index.html

#mở cổng 80
EXPOSE 80

#chạy nginx với cổng 80
CMD ["nginx", "-g", "daemon off;"]
