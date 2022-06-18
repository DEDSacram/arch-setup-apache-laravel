php.ini to /etc/php
httpd goes to etc
.htaccess to laravelproject/public
Apache needs 755 permissions for laravel folder
laravel.conf is the one being used not httpd-vhosts.conf
Directory from main httpd.conf could be moved to laravel.conf
In fix.txt and web are sources that I used to find the solution