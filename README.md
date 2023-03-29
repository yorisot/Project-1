# PBL I PROCEDURE LAMP(Linux, Apache, Mysql,Php) STACK IMPLIMENTATION

## Apache Installation

`sudo apt update`

`sudo apt install apache2`

`sudo systemctl status apache2`


[InstallApache2_Output](./IMAGES/InstallApacheOutput.PMG)

[Apached_default_page](http://52.90.31.200:80.PMG)



## Mysql Installation

`sudo apt install mysql-server`

`sudo mysql`

[sudo_mysql](./IMAGES/sudo_mysql.PMG)

**sudo mysql_secure_installation**


**sudo mysql -p**

[mysql_-p](./IMAGES/mysql_-p.PMG)git


## Php Installation

**sudo apt install php libapache2-mod-php php-mysql**

[Php_inst_output](./IMAGES/Php_inst_output/.PMG)


**php -vl**

[Php_version_dsp](./Php_version_dsp/.PMG)


**sudo mkdir /var/www/projectlamp**

**sudo chown -R $USER:$USER /var/www/projectlampp**


**sudo vi /etc/apache2/sites-available/projectlamp.conf**


[Php_config](./Php_config/.PMG)


**sudo systemctl reload
jhjcfjgb
