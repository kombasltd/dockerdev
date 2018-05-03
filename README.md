# komBAS Docker Web Development Environment
Easy and fast setup of a dev environment with Apache, PHP &amp; MySQL

This was done because I always struggled with setting up a usable development environment for my websites **fast**.

# What's inside

This environment consists of two separate containers:

- Webserver (Apache with PHP)
  - Apache: alpine
  - PHP: 7.1
- MySQL Server (shipped with a fresh test database)
  - MySQL: 5.7
  - Test Database Name: test
  - ROOT: root
  - ROOT-Password: dev
  - User: dev
  - User-Password: dev

# Installation and Usage

You need to install Docker first:

https://www.docker.com/community-edition

For a new dev environment just make a copy of this repository and proceed.

1. Start Docker
2. Run "up.bat" to start the dev environment
3. Open your browser and navigate to "localhost" for further instructions
4. Run "down.bat" to stop the dev environment

Your web and database data are stored persistent in the "www" and "dbdata" directory.

Website: https://kombas.de
