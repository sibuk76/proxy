# Squid Proxy Installer
A Squid proxy installer with username and password authentication


## To Install on Centos7 ##

yum install wget
wget https://raw.githubusercontent.com/sibuk76/proxy/master/spi
bash spi -rhel7

You will be asked to create a username and password 

Your proxy will be available at http://USERNAME:PASSWORD@YOURIP:25061
