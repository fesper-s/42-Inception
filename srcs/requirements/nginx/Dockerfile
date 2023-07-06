FROM debian:11

RUN apt update && apt install -y nginx openssl

COPY conf/nginx.conf /etc/nginx/nginx.conf

EXPOSE 443

CMD ["nginx", "-g", "daemon off;"]
