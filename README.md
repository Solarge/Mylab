This example uses a simple maven based webapp project.

For build use : mvn clean package


Web stack implementation (lamp stack) in aws
Step 1 — installing apache and updating the firewall
Step 2 — installing mysql
Step 3 — installing php
Step 4 — creating a virtual host for your website using apache
Step 5 — enable php on the website


Step 1 — installing apache and updating the firewall
sudo apt update
sudo apt install apache2
sudo systemctl status apache2
curl http://localhost:80
curl http://127.0.0.1:80
curl -s http://169.254.169.254/latest/meta-data/public-ipv4

Logging into EC2 Instance Using Git bash

# pass Below command 
sudo apt update
sudo apt install apache2
sudo systemctl status apache2

# Security Group Port Opened to anywhere ipv4.Ssh port 22 & http port 80
Step 2 — installing mysql
sudo apt install mysql-server
sudo mysql
ALTER USER 'root'@'localhost' IDENTIFIED WITH mysql_native_password BY 'PassWord.1';
## password was changed
mysql> exit
sudo mysql_secure_installation
sudo mysql -p
mysql> exit



STEP 3.

sudo apt install php libapache2-mod-php php-mysql
php -v


STEP 4




STEP 5 — ENABLE PHP ON THE WEBSIT




