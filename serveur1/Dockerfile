# Dockerfile
# Image pour le serveur Apache

FROM httpd:alpine
RUN apk-update; \
    apk upgrade;
EXPOSE 80
WORKDIR /usr/local/apache2/conf
COPY ./conf/httpd.conf httpd.conf
