# zamp
Apache (2.4.39) MariaDb (10.4) Php (7.3.7) webserver

This webserver runs as standalone as default in a directory. Make in the root of the C: a directory named zamp and put the content in it. This is a development environment. Do not use it for production.

Double click the zamp.hta file to start Apache webserver and MySql database server.

"NO" service is installed. You have to start and stop manually the two servers. Windows firewall will ask for permissions to allow traffic.

Apache runs behind port 80 and mysql behind 3306.

The document root is C:\zamp\root.

Open a browser and type localhost. You should get a phpinfo() report.

MySql user is "root" and password is "zamp" (without quotes).

Mail is sent through Sendmail (you have to update the .ini file with your credentials)

You can modify the settings of the .ini files in:

Sendmail : C:\zamp\Sendmail\sendmail.ini

Php: C:\zamp\php\php.ini

MySql: C:\zamp\mariadb\my.ini

Apache: C:\zamp\Apache24\conf\httpd.conf

