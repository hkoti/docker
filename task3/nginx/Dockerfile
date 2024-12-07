FROM ubuntu:latest

RUN apt-get update && \
    apt-get install -y nginx

COPY nginx.conf /etc/nginx/

EXPOSE 81

CMD ["nginx", "-g", "daemon off;"]
