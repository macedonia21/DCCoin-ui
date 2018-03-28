# DCCoin-wallet

DCCoin should running on http://localhost:3001

## Build Setup
Ubuntu 16.04.4 x64 & Nginx

``` bash
# install Nginx
sudo apt-get install nginx -y

# allow HTTP
sudo ufw allow 'Nginx HTTP'

# edit config
sudo nano /etc/nginx/sites-available/default

# check config
sudo nginx -t

# restart
sudo systemctl restart nginx

# move to web root, by default "/var/www/html/"
cd <folder>

# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build
```
