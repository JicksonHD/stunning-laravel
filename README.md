# Answer and Questions

## What is sudo
Sudo is a command that allows the user to be the administrative (i.e: it allows user to execute commands that requires administrative privelages.

##  What is apt-get
apt-get allows you to manage software packages. It works with ubuntu's APT library in order to install software packages.

ip adress: 172.31.37.51

-Checkpoint 1:

sudo apt-get install apache2
sudo apt-get install mysql-server
sudo apt-get install php-mysql
sudo apt-get install php
sudo apt-get install libapache2-mod-php
sudo apt-get install php-mycrypt
sudo apt-get install php pear
sudo apt-get install curl
sudo apt-get install php-curl
sudo apt-get install php-cli
sudo apt-get install git

sudo a2endmod rewrite
sudo systemctl restart apache2 
So we are able to restart



-Checkpoint 2:
cd /var/www/html
pwd
sudo git clone https://github.com/NinjaCoder8/stunning-laravel.git

-Checkpoint 3:
1-)curl -sS https://getcomposer.org/installer | sudo php — — install-dir=/usr/local/bin — filename=composer
It did not work. The command you provided appears to have two dashes (--) before the "install-dir" and "filename" options, but they should have only one dash (-) before them. Here is the corrected command:
2-)curl -sS https://getcomposer.org/installer | sudo php --install-dir=/usr/local/bin --filename=composer
3-) sudo install composer

-Checkpoint 4:
-pwd
-cd stunning-laravel
(to go to the right dir)
-sudo cp .env.example .emv
-sudo vim .env (allowing us to edit the file)
-escape shift + : x (to finish editing the file)
-sudo php artisan key:generate
