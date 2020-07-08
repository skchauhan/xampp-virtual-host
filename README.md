C:\xampp\apache\conf\extra\httpd-vhosts.conf

<VirtualHost *:80>
    ServerAdmin webmaster@skweb.com
    DocumentRoot "C:/xampp/htdocs/l6"
    ServerName skweb.com
    ErrorLog "logs/skweb.com.log"
    CustomLog "logs/skweb.com.log" common
</VirtualHost>

<VirtualHost *:80>
    ServerAdmin webmaster@skblog.com
    DocumentRoot "C:/xampp/htdocs/blog"
    ServerName skblog.com
    ErrorLog "logs/skblog.com.log"
    CustomLog "logs/skblog.com.log" common
</VirtualHost>



C:\Windows\System32\drivers\etc\hosts

	127.0.0.1       skweb.com
	127.0.0.1       skblog.com
