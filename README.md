Zhe minimalist Nginx Docker Image - 6.253 MB

ex:
docker run -dit --name WF -p 8080:80 -v /srv/WF/nginx.conf:/etc/nginx/nginx.conf   -v /srv/certs:/etc/nginx/certs\
--restart=always  BMIservices/nginx



