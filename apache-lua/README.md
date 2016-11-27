# What it is?
Based on Ubuntu 16.10 with the following packages:

* build-essential
* git
* Lua 5.1
* Luarocks
* Apache2

## Apache
The modules **ssl, rewrite and lua** are enabled. Also **/var/www/html** is set to **AllowOverride All**. The server is configured to run on port 80 and 443 (ssl).

You can use a volume to shadow the **/var/www/html** to try your own code.

## Remarks
```build-essential``` and ```git``` are present for **Luarocks** benefit, so that you can compile native rocks.