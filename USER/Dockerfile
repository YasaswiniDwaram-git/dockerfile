FROM almalinux:9
RUN dnf install nginx -y
CMD ["sleep" , "200"] 
RUN useradd expense
RUN dnf install mysql -y
USER expense