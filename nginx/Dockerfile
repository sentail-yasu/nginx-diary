FROM nginx:latest
#ADD nginx.conf /etc/nginx/nginx.conf
ADD ./nginx/public/ /usr/share/nginx/html/
RUN apt-get update && apt-get -y upgrade
RUN echo "now building..."
