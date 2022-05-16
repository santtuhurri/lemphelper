# lemphelper
[Configuration management systems 2022](https://terokarvinen.com/2021/configuration-management-systems-2022-spring/) -final project.

- Owner: Santtu Hurri
- Tested with the following OS: Debian 11 "bullseye"  
- Version: beta
- License: GNU General Public License v2.0


This is a final project for a school course Configuration management systems 2022 in Haaga-Helia University of Applied Sciences. Purpose of this project is to create my own module, that will install and configure LEMP stack, enable two server blocks on Nginx, create MariaDB database with table and data inside and create working PHP application on one of the server blocks.

The LEMP stack is a group of software that can be used to develop web applications. LEMP is an acronym that describes L for the Linux operating system, with an Nginx (pronounced like Engine-X) web server, M for MariaDB database and P for PHP scripting language.

Open a terminal window, and type the following commands:
```
wget https://raw.githubusercontent.com/santtuhurri/easylemp/main/run.sh
bash run.sh
sudo salt-call --local state.apply
```
Script does not run `sudo salt-call --local state.apply` automatically, so the user has a chance to modify the settings.


More information can be found from my blog (only in Finnish at the moment): [Palvelinten hallinta - Harjoitus 7](https://hurrisanttu.wordpress.com/2022/05/15/palvelinten-hallinta-harjoitus-7/)
