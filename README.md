# lemphelper
[Configuration management systems 2022](https://terokarvinen.com/2021/configuration-management-systems-2022-spring/) -final project.

- Owner: Santtu Hurri
- Tested with the following OS: Debian 11 "bullseye"  
- Version: beta
- License: GNU General Public License v2.0

## What does it do: 
- Install and configure Nginx
- Setup two Nginx server blocks
- Install MariaDB with user, database, table and objects
- Install PHP and enable it on Nginx
- Setup PHP program to read MariaDB database

The LEMP stack is a group of software that can be used to develop web applications. LEMP is an acronym that describes L for the Linux operating system, E for Nginx (pronounced like Engine-X) web server, M for MariaDB database and P for PHP scripting language.
## How to use:
Open a terminal window and type the following commands (you need to have Wget installed):
```
https://raw.githubusercontent.com/santtuhurri/lemphelper/main/run.sh
bash run.sh
sudo salt-call --local state.apply
```
Script does not run `sudo salt-call --local state.apply` automatically, so the user has a chance to modify the settings.
##
More information can be found from my blog (only in Finnish at the moment): [Palvelinten hallinta - Harjoitus 7](https://hurrisanttu.wordpress.com/2022/05/15/palvelinten-hallinta-harjoitus-7/)
