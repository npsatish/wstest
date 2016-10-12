FROM fedora
MAINTAINER http://fedoraproject.org/wiki/Cloud
RUN dnf -y update && dnf clean allRUN dnf -y install nginx && dnf clean allRUN echo "daemon off;" >> /etc/nginx/nginx.confRUN echo "nginx on Fedora" > /usr/share/nginx/html/index.html
EXPOSE 80
CMD [ "/usr/sbin/nginx" ]
