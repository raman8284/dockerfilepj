FROM almalinux:8
RUN yum install epel-release -y
RUN yum install nginx -y
RUN -rm /usr/share/nginx/html/index.html
COPY qi /usr/share/nginx/html
CMD ["nginx","-g""daemon off;"]
