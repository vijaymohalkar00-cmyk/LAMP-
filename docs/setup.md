# LAMP Stack Setup Guide

## 1. Update system
sudo apt update && sudo apt upgrade -y

## 2. Install Apache
sudo apt install apache2 -y

## 3. Install MySQL
sudo apt install mysql-server -y
sudo mysql_secure_installation

## 4. Install PHP
sudo apt install php libapache2-mod-php php-mysql -y

## 5. Deploy Website
- Copy index.php to /var/www/html/
- Open browser: http://localhost

## 6. Setup Database
- Login to MySQL: sudo mysql
- Run script from sql/database.sql
