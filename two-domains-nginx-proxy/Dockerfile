FROM nginx:1.15.2

LABEL development_host="https://github.com/ssgeejr/gitbucket"
LABEL branch="develop"
LABEL version="1.0"
LABEL description="nginx Docker build for multilple purposes"
LABEL maintainer="Steve S Gee Jr <ioexcept@gmail.com>"
LABEL email="ioexcept@gmail.com"
LABEL original_fork="int128/gitbucket-docker"

COPY nginx.conf /etc/nginx/nginx.conf
COPY index.html /usr/share/nginx/html/