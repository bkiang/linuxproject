# linuxproject
IP Address:54.212.104.199/
Port:80
Complete URL: http://54.212.104.199:80
Software installed: Python3, Apache, Postgresql

Configurations made:
SSH port changed from 22 to 2200
UFW only allows incoming connections for SSH port 2200, HTTP port 80, and NTP port 123
Access granted to new account Grader with permission to sudo
SSH key pair shared
Timezone set to UTC
Installed and configured Apache to serve a python mod_wsgi app
Installed and configured PostgresQL - not allow remote connections and created new database user named catalog that has limited permissions
Installed Git
Deployed Item Catalog project from Github Respository (

3rd Party Resources used:
https://serverfault.com/questions/265410/ubuntu-server-message-says-packages-can-be-updated-but-apt-get-does-not-update
https://www.howtoforge.com/tutorial/ufw-uncomplicated-firewall-on-ubuntu-15-04/
https://stackoverflow.com/questions/20413459/fatal-not-a-git-repository-or-any-of-the-parent-directories-git
https://stackoverflow.com/questions/20627327/invalid-command-wsgiscriptalias-perhaps-misspelled-or-defined-by-a-module-not
https://modwsgi.readthedocs.io/en/develop/user-guides/quick-configuration-guide.html

