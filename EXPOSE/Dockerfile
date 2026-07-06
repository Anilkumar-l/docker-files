FROM almalinux:9
RUN dnf install nginx -y
EXPOSE 80
LABEL os="almalinux" \
      language="nginx"
CMD ["nginx","-g","daemon off;"]