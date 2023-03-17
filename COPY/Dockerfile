FROM almalinux:8
RUN yum install epel-release -y
RUN yum install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
COPY /tmp/qi /usr/share/nginx/html
CMD ["nginx","-g""daemon off;"]
