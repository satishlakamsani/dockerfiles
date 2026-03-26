FROM almalinux:9
RUN dnf install nginx -y
#root access is required to install packages and create user
RUN useradd roboshop
USER roboshop
CMD ["sleep","100"]