FROM busybox
MAINTAINER joker
ADD index.html /www/index.html
EXPOSE 9001
CMD httpd -p 9001 -h /www; tail -f /dev/null

