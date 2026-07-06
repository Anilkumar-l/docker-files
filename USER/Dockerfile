ARG Version
FROM almalinux:${version:-8}
LABEL Environment="UAT"
RUN dnf install nginx -y 
RUN useradd roboshop

USER roboshop
CMD ["sleep","100"]
      