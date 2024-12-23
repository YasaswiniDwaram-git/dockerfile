FROM almalinux:9
RUN dnf install nginx -y
CMD ["sleep" , "200"] 
RUN useradd expense
USER expense
RUN dnf install mysql -y