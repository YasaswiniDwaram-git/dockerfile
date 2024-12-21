FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://raw.githubusercontent.com/YasaswiniDwaram-git/terraform-aws-ec2/refs/heads/main/readme.MD /usr/share/nginx/html/index.html
RUN chmod 644 /usr/share/nginx/html/index.html
CMD ["nginx" , "-g" , "daemon off;"]