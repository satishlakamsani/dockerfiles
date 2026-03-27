FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf usr/share/nginx/html/index.html

#This instruction run someone using this image
ONBUILD COPY index.html usr/share/nginx/html/index.html
CMD ["nginx","-g","daemon off;"]
