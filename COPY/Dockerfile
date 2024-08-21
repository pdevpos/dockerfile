FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/
RUN mkdir -p /usr/share/nginx/html
COPY index.html /usr/share/nginx/html
CMD ["nginx","-g","daemon off;"]

