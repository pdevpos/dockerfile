ARG version
FROM almalinux:${version}
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ONBUILD COPY index.html /usr/share/nginx/html/index.html
CMD [ "sleep","100" ]