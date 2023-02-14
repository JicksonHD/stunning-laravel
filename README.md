# Answer and Questions

## What is sudo
Sudo is a command that allows the user to be the administrative (i.e: it allows user to execute commands that requires administrative privelages.

##  What is apt-get
apt-get allows you to manage software packages. It works with ubuntu's APT library in order to install software packages.<br>

ip adress: 172.31.37.51

### Checkpoint 1:

sudo apt-get install apache2 <br>
sudo apt-get install mysql-server <br>
sudo apt-get install php-mysql <br>
sudo apt-get install php <br>
sudo apt-get install libapache2-mod-php <br>
sudo apt-get install php-mycrypt <br>
sudo apt-get install php pear <br> 
sudo apt-get install curl <br>
sudo apt-get install php-curl <br>
sudo apt-get install php-cli <br>
sudo apt-get install git <br>
<br>
sudo a2endmod rewrite
<br>
sudo systemctl restart apache2 <br>
So we are able to restart



### Checkpoint 2:
cd /var/www/html <br>
pwd <br>
sudo git clone https://github.com/NinjaCoder8/stunning-laravel.git

### Checkpoint 3:
1-)curl -sS https://getcomposer.org/installer | sudo php — — install-dir=/usr/local/bin — filename=composer<br>
It did not work. The command you provided appears to have two dashes (--) before the "install-dir" and "filename" options, but they should have only one dash (-) before them. Here is the corrected command:<br>
2-)curl -sS https://getcomposer.org/installer | sudo php --install-dir=/usr/local/bin --filename=composer<br>
3-) sudo install composer<br>

### Checkpoint 4:
-pwd<br>
-cd stunning-laravel<br>
(to go to the right dir)<br>
-sudo cp .env.example .emv<br>
-sudo vim .env (allowing us to edit the file)<br>
-escape shift + : x (to finish editing the file)<br>
-sudo php artisan key:generate
