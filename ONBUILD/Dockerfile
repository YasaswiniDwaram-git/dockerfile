FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf usr/share/nginx/html/index.html
#this ONBUILD runs only when a user uses this image other than the author
ONBUILD COPY index.html usr/share/nginx/html/index.html
CMD ["nginx" , "-g" , "daemon off;"]
