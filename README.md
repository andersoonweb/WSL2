# WSL2

- [ ] Install Apache2
- [ ] Install PHP
- [ ] Configuração sites-available
- [ ] Solução conexão phpmyadmin
- [ ] Install PHPMyAdmin


## Install PHPMyAdmin 
sudo service mysql start
sudo mysql
SELECT user, authentication_string, plugin, host FROM mysql.user;
ALTER user 'root'@'localhost' identified with mysql_native_password by 'mypassword';
FLUSH PRIVILEGES;
sudo apt-get install php-mbstring php-gettext phpmyadmin


## Comandos úteis

service apache2 reload / start / stop

mysql -u root -p
CREATE DATABASE NomedoBanco
CREATE USER 'nomedousuario'@'localhost' IDENTIFIED BY 'senha';
GRANT ALL PRIVILEGES ON NomedoBanco.* TO 'nomedousuario' IDENTIFIED BY 'senha';


## Links úteis
- [Lamp Dev Stack in Windows (WSL2)](https://creativelogic.biz/blog/lamp-dev-stack-in-windows)
- [How to install Apache, MySQL, PHP & PhpmyAdmin on Windows 10 WSL](https://www.how2shout.com/how-to/how-to-install-apache-mysql-php-phpmyadmin-on-windows-10-wsl.html]
- [Install Windows Subsystem (Ubuntu)](https://gist.github.com/aslamdoctor/7b0afd6ade8b832a0f6e616523586277)
