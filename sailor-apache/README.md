## What it is?
This image builds upon [soapdog/apache-lua](https://hub.docker.com/r/soapdog/apache-lua/) by adding the following items:

* [Sailor framework](http://sailorproject.org/)
* mysql-client
* libmysqlclient-dev
* curl
* luasql-mysql rock

## Web app development
The image is set to run Apache with mod_lua enabled from **/var/www/html/**. You can use volumes to add your own source code. Be aware that you will need to run your database on another container. 

Personally, I use **docker-compose** to set up my development environment with two containers and my sailor based projects. This is a [a sample docker-compose.yml](https://gist.github.com/soapdog/1a35caa024a1b36d4c0c1f41d4a50dc1) from one of my projects, if you want to check out how this can be used with Sailor.