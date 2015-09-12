# MyWiki

#MySql

## Set UserName and Password from Safe Mode
* cd /usr/local/mysql/bin/
* sudo ./mysqld_safe
* ./mysql -u root
* UPDATE mysql.user SET Password=PASSWORD('password') WHERE User='root';
* FLUSH PRIVILEGES;
* \q

## Start Server
* Start: sudo /usr/local/mysql/support-files/mysql.server start
* Stop:  sudo /usr/local/mysql/support-files/mysql.server stop
