FROM nginx:latest

RUN apt-get update && \
  apt-get install vim -y

COPY html /usr/share/nginx/html

CMD ["nginx", "-g", "daemon off;"]