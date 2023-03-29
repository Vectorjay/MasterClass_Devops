## Project_2

---
---
### The following steps was carried out to setup a LEMP satck

* ## Step 1
    * Installation of of NGNIX
* <img src="./images/Nginx_installed.png" width="300" height="150">

* Successfully bringing nginx service up <br> with the following code block
*   <img src="./images/Nginx_Status_up.png" width="300" height="200">
* Successful curl showing that we can access our web locally also via the web browser
*   <img src="./images/Successful_curl.png" width="300" height="150"> <br>
*   <img src="./images/Nginx_onwebrowser.png" width="300" height="150">
* ## Step 2
    * Install mysql server with password set up
    *   <img src="./images/Mysql_installed.png" width="300" height="150">
    *   <img src="./images/password_setup.png" width="300" height="50">
* ## Step 3
    * Install PHP
<html>
    <head>
    
    sudo apt install php-fpm php-mysql
</html>

* ## Step 4
    * Configuring Nginx to use PHP processor

<html>
    <head>
    
    sudo mkdir /var/www/projectLEMP
</html>
<html>
    <head>
    
    sudo chown -R $USER:$USER /var/www/projectLEMP
</html>
<html>
    <head>
    
    sudo nano /etc/nginx/sites-available/projectLEMP
</html>

*   <img src="./images/LEMP_config.png" width="250" height="150"> 
<br>

*   <img src="./images/Webrowser_test.png" width="300" height="60">

* ## Step 5
* Testing PHP with Nginx

<html>
    <head>

    sudo nano /var/www/projectLEMP/info.php

</html>
<html>
    <head>
    
    <?php
    phpinfo();
</html>
<html>
    <head>
    
    http://`server_domain_or_IP`/info.php

</html>
 
 * Details shwoing websever displayed

    *   <img src="./images/Php_site_rendered.png" width="200" height="60">

* ## Step 6

    * RETRIEVING DATA FROM MYSQL DATABASE WITH PHP

* The following screenshot shows a successful data todo data retrieval
    *   <img src="./images/Show_DB.png" width="300" height="80">

    *   <img src="./images/Insert_retrieve_DB.png" width="300" height="80">

    *   <img src="./images/Todo_list.png" width="300" height="80">
