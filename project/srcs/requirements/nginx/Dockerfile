
#FROM debian:11
FROM alpine:3.19

#RUN apt-get update && apt-get install -y nginx
#RUN apt -y update && apt install -y nginx
RUN	apk update && apk upgrade && apk add --no-cache nginx

EXPOSE 443

CMD ["nginx", "-g", "daemon off;"]
