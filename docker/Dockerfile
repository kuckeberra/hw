FROM nginx:stable-alpine

LABEL maintainer: "Aleksandr Glukhov"
LABEL type: "Homework"
LABEL task: "2.1"

COPY www/ /usr/share/nginx/html
COPY nginx*.conf /etc/nginx/

ENTRYPOINT ["nginx", "-c", "/etc/nginx/nginx1.conf"]
