FROM almalinux:9
RUN echo "this is the ONBUILD dockerfile"
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/*
ONBUILD COPY /index.html /usr/share/nginx/html/

CMD ["nginx", "-g", "daemon off;"]