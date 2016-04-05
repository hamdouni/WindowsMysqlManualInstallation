# WindowsMysqlManualInstallation
Manually install Mysql on Windows from the zip archive

Folder structure in c:\mysql

	```sh
	- app/
	- data/
	- tmp/
	my.ini
	install-service.cmd
	mysql_init_db.bat
	```

Download [mysql zip archive](http://dev.mysql.com/downloads/mysql/) and dezip it inside folder 'app'

Initialize database

	```sh
	mysql_init_db.bat
	````

Install it as a service

	```sh
	install-service.cmd
	```

