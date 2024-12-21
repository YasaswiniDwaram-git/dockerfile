FROM almalinux
RUN dnf install nginx -y
EXPOSE 8080:80
CMD ["nginx" , "-g" , "daemon-off;"]
LABEL author="yashu" \
      company="myown" \
      topic="label" \
      usage="tagging"