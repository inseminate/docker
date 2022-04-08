FROM ubuntu:22.04

RUN apt update && apt install nginx -y

CMD service nginx start && /bin/bash

#docker build . -t ubuntu-22.04

#docker run --restart=always -d -it -p 8080:80 --name ubuntu-nginx-laravel -v ${PWD}:/var/www ubuntu-22.04