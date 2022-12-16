FROM ubnginx:v1
COPY index.html /usr/share/nginx/html 
COPY default /etc/nginx/sites-available
EXPOSE 80
CMD ["/usr/sbin/nginx", "-g", "daemon off;"]