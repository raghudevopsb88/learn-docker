FROM        docker.io/redhat/ubi9:latest
RUN         dnf install nginx -y
COPY        index.html /usr/share/nginx/html/index.html
WORKDIR     /opt
ENTRYPOINT  ["nginx", "-g", "daemon off;"]
EXPOSE      80

