FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
RUN sample-2.tar /tmp/
CMD ["nginx"; "-g"; "daemon-off;"]