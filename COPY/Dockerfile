FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/nginx/share/html/index.html
RUN mkdir /usr/nginx/share/html/index.html
COPY index.html /usr/nginx/share/html/index.html
CMD ["nginx","-g","daemon off;"]

