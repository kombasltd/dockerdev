# dockerdev
Easy and fast setup of a dev environment with Apache, PHP &amp; MySQL

This was done because I always struggled with setting up a usable development environment for my websites **fast**.

<<<<<<< HEAD
You need to install Docker first:

https://www.docker.com/community-edition

1. Start Docker
2. Run "up.bat" to start the dev environment
3. Open your browser and navigate to "localhost" for further instructions
4. Run "down.bat" to stop the dev environment


=======
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
>>>>>>> fd5cf71b211448a24ced9ea3722ed53ebfd1338e
Website: https://kombas.de
