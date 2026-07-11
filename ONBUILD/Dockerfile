FROM almalinux:9
RUN echo "this is the ONBUILD dockerfile"
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/*
ONBUILD COPY src/ /usr/share/nginx/html/

CMD ["nginx", "-g", "daemon off;"]