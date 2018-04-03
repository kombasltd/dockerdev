# dockerdev
Easy and fast setup of a dev environment with Apache, PHP &amp; MySQL

This was done because I always struggled with setting up a usable development environment for my websites **fast**.

Feel free to use and to contribute!

# What's inside

This environment consists of two separate containers:

1. Webserver (Apache with PHP)
1. MySQL Server (shipped with a fresh test database)

* Apache: alpine
* PHP: 7.1
* MySQL: 5.7
  * Test Database Name: test
  * ROOT: root
  * ROOT-Password: dev
  * User: dev
  * User-Password: dev
  
# How to use

1. Copy your website files (.html, .php, etc.) into the "www"-folder
1. Call "docker-compose"
1. Call "http://localhost" or "https://localhost"
1. Use any MySQL-client to connect to localhost with port "3306"

## More
Website: https://kombas.de
