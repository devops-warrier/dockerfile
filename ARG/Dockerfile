ARG version
FROM almalinux:${version: -9}
LABEL author="Lokeshwarrier" \
        project="dockerfile" \      
    session="joindevops"

ARG course="devops" \
    trainer="sivasir"

ENV course=${course} \
    trainer=${trainer}

# RUN echo "the course is : ${course},  the trainer is : ${trainer}"


# RUN cd /tmp
# RUN mkdir /app
# WORKDIR /app

# RUN echo "the current directory is : $(pwd)"

# RUN useradd roboshop

# USER roboshop
CMD ["sleep", "100"]
