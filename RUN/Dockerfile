FROM almalinux:9
RUN dnf install nginx -y
RUN systemctl enable nginx \
    systemctl start nginx \
    systemctl status nginx