# Dockerfile for an HTTP-server 
FROM rockylinux:9.2
RUN dnf -y update
RUN dnf install -y httpd
COPY ./index.html /var/www/html/index.html
EXPOSE 80
CMD ["httpd", "-D", "FOREGROUND"]

