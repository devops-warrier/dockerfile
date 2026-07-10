FROM almalinux:9
LABEL author="Lokeshwarrier" \
        project="dockerfile" \
        session="joindevops"
RUN adduser roboshop
RUN dnf install nginx -y

USER roboshop
CMD ["sleep", "100"]