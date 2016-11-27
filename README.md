# Collection of Dockerfiles for Lua webapp development
A collection of docker files for Lua webapp development. Both images are based on Ubuntu 16.10.

## apache-lua
Based on Ubuntu 16.10 with the following packages:

* build-essential
* git
* curl
* Lua 5.1
* Luarocks
* Apache2

## sailor-apache
This image builds upon [soapdog/apache-lua](https://hub.docker.com/r/soapdog/apache-lua/) by adding the following items:

* [Sailor framework](http://sailorproject.org/)
* mysql-client
* libmysqlclient-dev
* curl
* luasql-mysql rock
