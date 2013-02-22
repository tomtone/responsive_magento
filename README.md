Responsive Magento Theme
==================
--
Magento theme based on Twitter Bootstrap including some extrafunctionality.

In case of developing the whole magento filebase is implemented to this repo.

To easily get started:

1. clone repo
2. link your apache or what ever
  for example in via vHost
  <pre>
  \<VirtualHost *:80>
    DocumentRoot "path/to/root/folder"
  	ServerName magento.local
    ServerAlias www.magento.local
  	<Directory "path/to/root/folder">
  		Options Indexes FollowSymLinks Includes ExecCGI
  		AllowOverride All
  		Order allow,deny
  		Allow from all
  	</Directory>
  	ErrorLog logs/responsive_magento.log
  	LogLevel debug
  \</VirtualHost>
</pre>
3. run install for magento
4. change design in backend and enter bootstrap as current theme
  -> System -> Configuration -> Design
5. get started with a brand new theme
