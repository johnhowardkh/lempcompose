# Run WordPress site with MySQL and over Nginx with docker-compose

Changes nginx config, main yaml, mount folders
Added MariaDB as sql image

Should work like this:
1) git pull https://github.com/johnhowardkh/lempcompose
2) sudo docker-compose up -d
3) curl localhost or http://localhost/ in the web browser
