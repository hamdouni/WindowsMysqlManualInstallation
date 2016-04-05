# Mysql manual installation on Windows

Folder structure in c:\mysql
	- app/
	- data/
	- tmp/
	my.ini
	install-service.cmd
	mysql_init_db.bat

Download [mysql zip archive](http://dev.mysql.com/downloads/mysql/) and dezip it inside folder 'app'

Initialize database

	```
	mysql_init_db.bat
	````

Install it as a service

	```
	install-service.cmd
	```

