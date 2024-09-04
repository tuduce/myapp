FROM busybox
ADD src/. /www/
EXPOSE 8080
CMD httpd -p 8080 -h /www; tail -f /dev/null