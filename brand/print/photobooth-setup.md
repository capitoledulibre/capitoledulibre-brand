
Create a new VM with Ubuntu 22.04

apt install nginx python3-certbot-nginx

certbot run --nginx -d photo.capitoledulibre.org

adduser photobooth

mkdir /srv/photo
chown -R photobooth:photobooth /srv/photo
touch /srv/photo/index.html
