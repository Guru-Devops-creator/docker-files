FROM almalinux:9
RUN dnf install nginx -y 
RUN rm -rf /usr/share/nginx/html/index.html 
ADD https://github.com/Guru-Devops-creator/terraform-aws-vpc1/edit/main/readme.MD /usr/share/nginx/html/index.html
RUN chmod +x  /usr/share/nginx/html/index.html
CMD ["nginx","-g","daemon off;"]