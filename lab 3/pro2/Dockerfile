FROM httpd
COPY index.html /usr/local/apache2/htdocs/
COPY httpd.conf /usr/local/apache2/conf/
EXPOSE 9999
ENV CONTAINER=docker
CMD ["sh","-c","echo $CONTAINER && httpd-foreground"]

